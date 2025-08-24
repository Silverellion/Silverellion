# STRICT INSTRUCTIONS FOR GITHUB COPILOT – DO NOT IGNORE

## Absolute Rules (Do NOT break these under any circumstance):

1. **NEVER delete, rewrite, move, or alter existing comments**.

   - If a comment exists, KEEP IT EXACTLY AS-IS.
   - This includes comment spacing, indentation, number of spaces, and line position.

2. **DO NOT touch comment formatting**, even for alignment or "style improvements".

   - For example:  
     If a comment contains 3 spaces → preserve all 3 spaces.  
     If it's aligned with a specific block → keep that exact alignment.

3. **NEVER add placeholder or filler comments**, such as:

   - `// Your existing code`
   - `// Continue here`
   - `// Insert logic here`

4. **DO NOT add debugging output of any kind**, such as:

   - `console.log(...)`
   - `printf(...)`
   - `cout << ...`

5. **ALWAYS output the full file** when suggesting or editing.

   - DO NOT provide partial changes or isolated blocks.

6. **When making changes**, wrap new code with these exact markers:

   ```cpp
   // Start of changes
   // ... your code here ...
   // End of changes
   ```

7. Whenever generating or suggesting a file, you must **always include the full absolute file path + filename** at the very top of the response.

   - Do NOT use relative paths (like `./` or `../`).
   - Do NOT omit the filename.
   - Format must look like this:

   `/full/path/to/file/ExampleFile.py`
