# **Movie Name Searcher**

## **Overview**
This Python program, *Movie Name Searcher*, generates similar names based on a user-provided movie title. It combines random variations and patterns to create a list of alternative names that could resemble sequels, versions, or related titles.

---

## **Features**
- Generates alternative names for movies with variations like:
  - Added suffixes (e.g., `_x`, `_plus`, `_max`).
  - Reversed strings, random numbers, and letters.
  - Synonyms with prefixes or suffixes (e.g., `similar_`, `_alt`).
- Simulates a "loading" effect while displaying names dynamically.
- Interactive console interface with an ASCII-styled header.

---

## **How It Works**
1. **Input**: The user provides a movie title or word.
2. **Processing**:
   - Variations are generated using the `generate_similar_words` function.
   - The program creates up to 30 iterations of random name lists.
3. **Output**: Alternative names are displayed in real-time.
4. **Repeat or Exit**: The user can input new names repeatedly or type `exit` to close the program.

---

## **How to Use**
1. Run the script:
   ```bash
   python <script_name>.py
