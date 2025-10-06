# Part 1 - Decisions and ifs

- Declare variables A and B, subtract A from B and display the result.

```mermaid
graph TD
	s([start]) --> a
  a["A = 1"] --> b["B = 5"] -->
  c["C = B - A"] --> d[\Display C\] --> n([end])
  
```

- Ask the user for a temperature in °C, convert it to °F using the formula F=(C×9/5)+32 and display the result.

```mermaid
graph TD
  s([start]) --> a[\Ask for temp in °C\]
	--> c[Store in variable C] --> f["F = (C*9/5) + 32"] -->
	d[\Display F\]
```

- Determine if a number is divisible by 7, when the number is divisible show on screen “the number is divisible by 7”, otherwise display on screen “the number is not divisible by 7”.

```mermaid
graph TD
  Ms([start]) --> a[\Ask for number\]
	--> b[Store in variable NUM] --> c{Is NUM % 7 == 0?}
	c --> |True|e[\Display 'the number is divisible by 7'\]--> en
	c --> |False|f[\Display 'the number is not divisible by 7'\] --> en
	en([end])
```

- Ask the user for 3 numbers, determine which one is the biggest number and print “the biggest number is: ” + number

```mermaid
graph TD
  Ms([start]) --> a[\Ask for number\] --> b[Store in variable A] -->
  c[\Ask for number\] --> d[Store in variable B] -->
  e[\Ask for number\] --> f[Store in variable C] --> g{Is A >= B?}
  g --> |True|h[biggest == A] --> j
  g --> |False|i[biggest == B] --> j
  j{Is biggest >= C?}
  j --> |False|k[biggest = C] --> l
  j --> |True|l
  l['The biggest number is:' + number] --> en([end])
```

# Part 2 - Cycles

- Ask the user for 8 numbers and display the mean of those numbers. Use a cycle.

```mermaid
graph TD
  Ms([start]) --> b[count = 0] --> c[sum = 0] --> d{Is count < 8?}
  d --> |True|e[\Ask for number\] --> f[sum = sum + number] --> h[count = count + 1] --> d
  d --> |False|g[mean = sum / 8] --> i[\Display mean\] --> n([end])
```

- Display the first 10 numbers of the fibonacci sequence.

```mermaid
graph TD
  Ms([start]) --> a[N1 = 0] --> b[N2 = 1] --> c[count = 0] --> d1[\Display N1 and N2\] --> d{Is count < 8?}
  d --> |True|e[N3 = N2 + N1] --> i1[\Display N3\] --> g[N1 = N2] --> h[N2 = N3] --> i[count = count + 1] --> d
  d --> |False|n([end])
```

- Ask the user for a number and print all the collatz conjecture series.

```mermaid
graph TD
  Ms([start]) --> a[\Ask for number\] --> b[Store in variable num] --> pr1[\Display num\] --> c{Is num == 1?}
  print[\Display num\]
  c --> |True|pr[\Display num\] --> n([end])
  c --> |False|d{Is num % 2 == 0?}
  d --> |True|e[num = num / 2] --> print --> c
  d --> |False|f["num = (num * 3) + 1"] --> print
```