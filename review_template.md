# Movie Review Template Instructions

When provided with a **Movie Title**, generate a new markdown file named `[movie_title_in_snake_case].md` with the following structure.

---

## File Structure

### 1. Detailed Plot Summary (Spoilers Included)
* **Format:** Wrap this entire section in a single HTML comment block (`<!-- ... -->`) at the top of the file.
* **Content:** A detailed, multi-paragraph breakdown of the entire plot from start to finish (including twists and the ending) to help the writer recall the whole movie.

### 2. Chronological Scene Breakdown
* **Format:** Each scene bullet point must be generated as its own **individual HTML comment block**, with a blank line in between. This allows the writer to type their review thoughts directly between the scenes.
  * *Example output format:*
    ```markdown
    <!-- 1. Suzy arrives at the dance academy in Freiburg on a stormy night. -->

    <!-- 2. Suzy witnesses Pat Hingle fleeing the academy in terror. -->
    ```
* **Content:** A chronological list of the sequence of events, providing roughly **5–10 bullets per hour** of the movie's runtime.

### 3. Themes & Analysis Topics
* **Format:** Wrap this section in a single HTML comment block (`<!-- ... -->`) at the bottom of the file.
* **Content:** A list of major themes, cinematic techniques, or artistic aspects commonly discussed in relation to this movie. Do not include specific critics' opinions or reviews to avoid bias.