#!/bin/bash

echo "=== 🐧 Freestyle Linux System Report ==="
echo "User        : $USER"
echo "Hostname    : $(hostname)"
echo "Uptime      : $(uptime -p)"
echo "Date & Time : $(date)"
echo "OS          : $(uname -o)"
echo "Kernel      : $(uname -r)"
echo "Shell       : $SHELL"
echo

echo "--- 🧠 Memory Info ---"
free -h
echo

echo "--- 💾 Disk Usage ---"
df -h --total | grep total
echo

echo "--- 👥 Logged-in Users ---"
who
echo

echo "--- 💡 Random Motivation ---"
shuf -n 1 <<EOF
"Stay hungry, stay foolish." – Steve Jobs
"Talk is cheap. Show me the code." – Linus Torvalds
"First, solve the problem. Then, write the code." – John Johnson
"Code is like humor. When you have to explain it, it’s bad." – Cory House
EOF

echo
echo "=== ✅ Report Complete ==="
