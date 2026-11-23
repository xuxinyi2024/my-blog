---

title: "one2n Loop Experiment"
date: 2026-11-23T20:00:00+08:00
draft: false
tags: ["Linux","Shell"]
categories: ["Experiment"]

---

Practice the for loop in shell script,printing numbers from 1 to n.

```bash
read -p "Please enter n:" n
for((i=1;i<=n;i++))
do
  echo $i
done




