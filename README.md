# Chinese Internet Slang Dictionary Data

This repository contains the data for the Chinese Internet Slang Dictionary project. It's a collection of modern Chinese internet slang words with their meanings, usage examples, and scenarios in English.

## Structure

Each slang word is stored as a YAML file in the `content/slang` directory with the following format:

```yaml
word: "slang-word"
pinyin: "pinyin-pronunciation"
meaning: "English meaning"
description: "Detailed description in English"
examples:
  - "Example 1 in Chinese (English translation)"
  - "Example 2 in Chinese (English translation)"
tags:
  - "relevant-tag-1"
  - "relevant-tag-2"
usage_scenarios:
  - "Usage scenario 1"
  - "Usage scenario 2"
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork this repository
2. Create a new YAML file in `content/slang/` directory
3. Name the file with the slang word (e.g., `yyds.yaml`)
4. Follow the template format above
5. Submit a Pull Request

### Guidelines

- Use clear and concise English for descriptions
- Include accurate pinyin
- Provide real-world examples
- Add relevant tags for categorization
- Describe common usage scenarios
- Include both Chinese and English in examples

## License

This project is licensed under the MIT License.