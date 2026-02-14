# Lecture 2: Statistics — Sampling & Experimental Design 📊

This lecture covers experimental design, sampling methods, and sampling error — foundational concepts in statistics and data science.

---

## 1️⃣ Design of Experiment (DOE)

Design of Experiment is a structured method to **collect data under controlled conditions** to determine cause-and-effect relationships.

In experiments, the researcher **actively manipulates variables**.

### Example

A company tests whether a new fertilizer increases crop yield.

- Group A → Old fertilizer
- Group B → New fertilizer
- Compare crop yield

Here, fertilizer type is the **treatment variable**.

---

## 2️⃣ Observational Study

In an observational study, researchers **do not manipulate variables**. They only observe and record data.

### Example

A researcher studies whether people who exercise live longer.

- No one is forced to exercise
- Researcher simply observes behavior

---

## 3️⃣ Difference: Experiment vs Observational Study

| Feature           | Experiment                    | Observational Study |
| ----------------- | ----------------------------- | ------------------- |
| Variable Control  | Researcher controls variables | No control          |
| Cause & Effect    | Can establish                 | Cannot confirm      |
| Random Assignment | Yes                           | No                  |
| Example           | Clinical trial                | Survey research     |

---

## 4️⃣ What is Random?

Random means:

> Every possible outcome has an equal chance of occurring.

### Example

- Tossing a fair coin
- Selecting students using a random number generator

---

## 5️⃣ Simple Random Sample (SRS)

A sample where **every individual in the population has an equal probability of being selected**.

### Example

Population: 1000 students
Sample: 100 students

Select 100 students using a random number generator.
Each student has an equal chance of selection.

---

## 6️⃣ Convenience Sampling

Sampling based on **ease of access**.

⚠️ Often biased and not representative.

### Example

Surveying only students from your own classroom.

---

## 7️⃣ Systematic Sampling

Select every _kth_ individual from a population list.

### Formula

k = Population Size / Sample Size

### Example

Population = 1000
Sample = 100

k = 1000 / 100 = 10

Select every 10th person from the list.

---

## 8️⃣ Stratified Sampling

Population divided into **homogeneous subgroups (strata)**.
Random samples are taken from each group proportionally.

### Example

University population:

- 60% Male
- 40% Female

Sample of 100:

- 60 males
- 40 females

Ensures proportional representation.

---

## 9️⃣ Cluster Sampling

Population divided into **naturally occurring groups (clusters)**.

Randomly select entire clusters.

### Example

A city has 20 schools.
Randomly select 5 schools.
Survey all students in those selected schools.

---

## 🔟 Sampling Error

Sampling error is the difference between:

> Sample Statistic and Population Parameter

### Concept

Sampling Error = Sample Mean − Population Mean

### Example

Population average income = $50,000
Sample average income = $48,000

Sampling error = $2,000

Sampling error occurs because we study a sample, not the entire population.

---

# 📌 Summary

- Experiment → Manipulates variables
- Observational Study → Only observes
- Random → Equal probability
- Simple Random Sample → Equal selection chance
- Convenience Sampling → Easy but biased
- Systematic Sampling → Every kth element
- Stratified Sampling → Divide by category
- Cluster Sampling → Select whole groups
- Sampling Error → Difference between sample and population
