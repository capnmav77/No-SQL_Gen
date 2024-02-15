# No-SQL Injection Dataset

![DOI](https://zenodo.org/badge/670473747.svg)

This repository contains a curated collection of  400 NoSQL injection commands, structured in a JSON format. Each entry includes two components: `"text"` and `"label"`. The `"text"` component encapsulates the payload of the NoSQL injection attempt, while the `"label"` component is a Boolean integer indicating whether the command is benign (`0`) or malicious (`1`). This dataset is designed to aid researchers and developers in studying the nature of NoSQL injection attacks and improving the security of applications that interact with NoSQL databases.

## Dataset Structure

```json
{
  "text": "<no-sql-payload>",
  "label": <boolean>
}
```

## Purpose

The primary purpose of this dataset is to assist in the development of machine learning models to detect NoSQL injection attempts and to serve as a benchmark for evaluating the effectiveness of security solutions against such attacks.

## Usage

Developers and security professionals can use this dataset to:

- Train machine learning models for NoSQL injection detection.
- Test the robustness of existing security measures.
- Understand the patterns and characteristics of NoSQL injection attacks.

## References

For a deeper understanding of NoSQL injection attacks, please refer to the following resources:

- Les NOSQL injections Classique et Blind: Never trust user input - Geluchat
- Testing for NoSQL injection - OWASP/WSTG
- NoSQL injection wordlists - cr0hn
- NoSQL Injection in MongoDB - JUL  17,  2016 - Zanon
- Burp-NoSQLiScanner

## Contributions

Contributions to enhance the dataset, such as adding new entries or improving the annotation, are welcome. Please submit pull requests or open issues to discuss improvements.

## Contact

For any questions or concerns regarding this dataset, please contact the maintainers through the GitHub issue tracker.
