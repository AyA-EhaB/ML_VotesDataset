# Congressional Voting Records

This dataset contains voting records of members of the U.S. House of Representatives during the 98th Congress in 1984. The data represents how each congressman voted on 16 different issues that were debated and voted on in Congress. The goal of this dataset is to predict the political party affiliation of a congressman (whether they are a Democrat or Republican) based on their voting behavior.

## Dataset Overview

The dataset contains 435 rows, each representing a single congressman or congresswoman.

### Attributes (Columns)

- **Party**: The target label indicating whether the congressman is from the Democratic Party or the Republican Party.
  
- **Voting on Issues**: There are 16 columns representing key political issues that were voted on. Each column indicates how the congressman voted on that issue:
  - `y`: Yes vote
  - `n`: No vote
  - `?`: Abstained or unknown (missing vote)

### Some of the issues that were voted on include topics like:
- **Handicapped infants**: Whether to provide assistance to handicapped infants.
- **Water project cost-sharing**: Whether the government should fund water projects.
- **Defense spending**: How much money should be allocated to defense.
- **Education spending**: How much the government should spend on education.
- **Foreign aid**: Whether to provide financial assistance to other countries.

## What Does the Data Represent?

The data reflects how each congressman voted on 16 critical political issues. By looking at how they voted (yes, no, or abstained), it’s possible to predict whether they are a Democrat or a Republican.

For example:
- If a congressman consistently voted **yes** on issues related to education spending or social welfare, they might be classified as a **Democrat**.
- If they voted **no** on these issues but supported military spending, they might lean more toward the **Republican** side.

The **Party** column (the target variable) tells us whether a congressman belongs to the Democratic Party or the Republican Party based on their voting pattern.
