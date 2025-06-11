
# 👋 Hi, I’m @baokhanh1701

> “It compiles. Ship it.”

## 🧠 About Me
- 🎓 CS graduate from Ho Chi Minh University of Technology
- ☁️ Currently clouding around as a Cloud Engineer @ NEC Vietnam
- 🐛 I break things until they work. Or until I find a bug. Whichever comes first.  
- 🧪 Passionate about pushing buttons I shouldn’t and enabling features that were never meant to be enabled.  
- 🧘‍♂️ Deadlines? Oh, you mean those `gentle suggestions` from the void? 

## 💀 Current Situation

```bash
while true; do
  timestamp=$(date +"%T")
  mood=$(shuf -n1 -e "😵‍💫" "🔥" "💀" "🤡" "🧠" "☕" "🪦")
  log_level=$(shuf -n1 -e "INFO" "WARN" "ERROR" "CRITICAL" "DEBUG")
  message=$(shuf -n1 -e \
    "Rebooting my will to live..." \
    "StackOverflow is down. Panic.")
  echo "[$timestamp] [$log_level] $mood $message"
  sleep $((RANDOM % 3 + 1))
done
```
