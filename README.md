# CoderDecoder Project

The **CoderDecoder** project is a web-based tool that allows users to encode and decode messages using the Caesar Cipher algorithm. This interactive tool offers several customizable options like shift key, modulo, alphabet, letter case handling, and foreign character removal.

## Features

- **Encode/Decode Modes**: Choose between encoding or decoding messages.
- **Shift Key**: Set the Caesar Cipher shift value.
- **Modulo**: Define the modulus value to wrap around the character set.
- **Custom Alphabet**: Use a custom alphabet (default: `abcdefghijklmnopqrstuvwxyz0123456789`).
- **Letter Case Handling**: Choose whether to maintain the letter case, convert to lowercase, or convert to uppercase.
- **Foreign Characters**: Remove or ignore foreign characters that are not in the custom alphabet.

## Getting Started

To run the **CoderDecoder** project locally, follow these steps:

### Prerequisites

You only need a modern web browser to use this tool.


### How to Use

1. **Select Mode**: Choose between **Encode** or **Decode** based on your task.
2. **Enter Text**:
   - For encoding, enter **plaintext**.
   - For decoding, enter **ciphertext**.
3. **Adjust Settings**:
   - **Shift Key**: Set the number of positions for the cipher.
   - **Modulo**: Adjust the modulus (default is `36`).
   - **Custom Alphabet**: Optionally, enter a custom character set.
   - **Letter Case**: Select whether to keep the case as is, convert to lowercase, or convert to uppercase.
   - **Foreign Characters**: Decide whether to remove or ignore foreign characters.
4. **Submit**: Click **Submit** to perform the cipher operation.
5. **Output**: The resulting encoded or decoded message will appear in the output section.

### Example Use Case

- **Encode a Message**:
   - Set the mode to **Encode**.
   - Enter the plaintext message (e.g., `Hello World`).
   - Set the **Shift Key** to `3`.
   - Click **Submit** to get the encoded message (e.g., `Khoor Zruog`).
  
- **Decode a Message**:
   - Set the mode to **Decode**.
   - Enter the encoded message (e.g., `Khoor Zruog`).
   - Set the **Shift Key** to `3`.
   - Click **Submit** to get the decoded message (e.g., `Hello World`).

## Customization Options

- **Shift Key**: Controls how far each letter is shifted in the Caesar Cipher.
- **Modulo**: The modulus for wrapping around the character set.
- **Alphabet**: You can customize the character set used for encoding/decoding.
- **Letter Case**: Choose whether to maintain the original letter case or convert all letters to lowercase/uppercase.
- **Foreign Characters**: You can choose to either remove or ignore characters that aren't in the specified alphabet.

## Technologies Used

- **HTML**: The webpage structure.
- **CSS**: For styling (optional).
- **JavaScript**: The main logic behind encoding and decoding messages using the Caesar Cipher.

## License

This project is open-source and available under the [MIT License](LICENSE).
