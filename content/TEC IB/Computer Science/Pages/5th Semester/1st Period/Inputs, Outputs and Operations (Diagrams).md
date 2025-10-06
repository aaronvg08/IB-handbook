- Write a program that asks for two numbers and shows their arithmetic mean.

```mermaid
graph TD
  s([start]) --> a[\Ask for number\] --> b[Store in variable A] -->
  c[\Ask for number\] --> d[Store in variable B] -->
  r["result = (A + B) / 2"] --> p[\Print result\] --> n([end])
```

- Write a program that asks for the weight (in kilograms) and height (in meters) of a person and calculates their body mass index (BMI), to one decimal place.

```mermaid
graph TD
  s([start]) --> a[\"Ask for weight (kg)"\] --> b[Store in variable W] -->
c[\"Ask for height (m)"\] --> d[Store in variable H] --> bmi["bmi = w / (h ** 2)"]
--> o[\"Display BMI"\] --> n([end])
```

- Write a program that asks for temperature in Celsius and prints that temperature in Fahrenheit.
```mermaid
flowchart TD

s([start]) --> a[\"Ask for temperature (°C)"\] --> b[Store in variable C] -->

c["F = (C * 1.8) + 32"] --> f[\Display F\] --> n([end])
```

- Write a program that receives as input the lengths of the two legs of a right triangle $a$ and $b$, and that outputs the length of the hypotenuse $c$, given by the Pythagorean theorem: $c^2 = a^2 + b^2$.

```mermaid
flowchart TD

    s([start]) --> a[\"Ask for a"\] --> b[Store in variable A] --> c[\"Ask for b"\]

    --> d[Store in variable B] --> e["C = ((a** 2) + (b** 2)) ** 0.5"]

    --> f[\"Display C"\] --> n([end])
```

A student wants to know what grade he needs in the third exam to pass a subject. The 3 exams are average using the following formula, where $E_1$, $E_2$ and $E_3$ are the 3 grades of the exams.

$$
  G_E = \frac{E_1 E_2 E_3}{3}
$$

The final grade is calculated with the following formula, where $G_E$ is the exams average and $L$ is the lab grade.

$$
F=0.7G_E + 0.3L
$$

Write a program that asks the user for the grades of the first two exam grades and lab grade, and print the grade that the student needs to pass the class with a final grade of 60.

```mermaid
 flowchart TD

    s([start]) --> a[\"Ask for first exam"\] --> b[Store in variable E1] --> c[\"Ask for second exam"\]

    --> d[Store in variable E2] --> h[\"Ask for lab"\] --> j[Store in variable L]

    --> e["min = (3 * (60 - (0.3 * L))) / 0.7 - E1 - E2"]

    --> f{Is min < 0?}

    f --> |True|k[\"Display 'Any grade will do'"\] --> n

    f --> |False|l{Is min > 100?}

    l --> |True|v[\"Display 'You cannot have 60 anymore :('"\] --> n

    l --> |False|m[\"Display min"\]

    --> n([end])
```

