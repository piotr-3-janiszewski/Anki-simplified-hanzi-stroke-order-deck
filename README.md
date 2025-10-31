# Simplified hanzi stroke order Anki deck

This project provides an **Anki deck** designed to help learners practice **writing Chinese characters (汉字 hànzì)** in order of frequency and stroke order.  
It combines open datasets and libraries to create a structured, frequency-based handwriting learning experience.

---

## Overview

The deck includes:
- **Common characters ranked by frequency**, based on a large-scale corpus.
- **Stroke order animations** generated from the [makemeahanzi](https://github.com/chanind/hanzi-writer-data) dataset.
- **Still images** for each character showing stroke numbers.
- **Compressed stroke data** which is dynamically decompressed within Anki during review.
- **Simplified Chinese** focus (简体字 jiǎntǐzì).
- One note per character, with:
  - Serial number (ordering)
  - Character display
  - Frequency coverage rate
  - **Pinyin pronunciation**
  - Definition(s)
  - Etymology type and hint
  - Radical
  - Stroke order animation
  - Stroke-numbered static image

**Important:** After importing the deck, you must copy the media files from the collection into the `collection.media` directory. You can access it via `Tools -> Check Media -> View Files` in Anki.

---

## Example Notes

Below are a few example cards included in the deck:

| Serial | Character | Coverage (%) | Pinyin | Definition | Etymology Type | Etymology Hint | Radical |
|--------|-----------|--------------|--------|------------|----------------|----------------|--------|
| 1      | 的        | 4.05         | de     | aim, goal; of; possessive particle; -self suffix |  |  | 白 |
| 2      | 一        | 5.91         | yī     | one; a, an; alone | ideographic | Represents heaven (天), earth (旦), or the number 1 | 一 |
| 3      | 了        | 1.83         | le liǎo | clear; to finish; particle of completed action | pictographic | A child swaddled in blankets; compare 子 | 亅 |
| 4      | 是        | 1.66         | shì    | to be; indeed, right, yes; okay | ideographic | To speak 日 directly 疋 | 日 |
| 5      | 不        | 1.57         | bù     | no, not, un-; negative prefix | ideographic | A bird flying toward the sky 一 | 一 |

---

## Example Media

The deck includes example images to show what a note looks like. These images are included in the media files:

- ![Example 1](example1.jpg)
- ![Example 2](example2.jpg)
- ![Example 3](example3.jpg)

These illustrate both the **animated stroke order** and the **static stroke-number images** that accompany each card.

---

## Data Sources

### 1. Hanzi Stroke Data
- **Source:** [Make Me a Hanzi](https://github.com/chanind/hanzi-writer-data)  
- **License:** [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)  
- **Description:**  
  JSON files describing stroke paths, medians, and structure for over 9,000 Chinese characters.  
  The stroke data is **compressed in the deck** to reduce size and decompressed dynamically during review.

### 2. Character Frequency List
- **Source:** 北京语言文化大学 (Beijing Language and Culture University)  
- **Dataset:** Frequency list based on a **2.5 billion–character corpus** of modern Chinese.  
- **Format:** Excel spreadsheet (可下载文件).  
- **Usage:** Used to order characters by real-world usage frequency.  
- **Reference:**  
  北京语言文化大学汉语语料库中心. 《现代汉语常用字频率表》.  

---

## How to Use

1. Open Anki.
2. Go to *File → Import...*
3. Select the provided `.apkg` file.
4. Copy the media files into the `collection.media` folder via `Tools -> Check Media -> View Files`.
5. Review cards to learn characters in frequency order.
