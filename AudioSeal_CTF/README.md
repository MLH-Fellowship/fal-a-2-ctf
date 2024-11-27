# 🎵 **The Great Meta AudioSeal CTF** 🔐

## 🌟 The Story 🌟

Deep in the labs of a secret organization, a mysterious flag has been **hidden across multiple audio files**. 🕵️‍♂️ These files contain fragments of a highly classified message, **watermarked using the Meta's powerful AudioSeal technology**. 

But there’s a catch… the files have been jumbled in random order! 🤯

Your mission, should you choose to accept it, is to:
- 🧩 Extract the hidden watermarked fragments from the audio files.
- 🔄 Reorder the fragments to reconstruct the full binary message.
- 🔓 Decode the binary message to reveal the **secret flag**.

Oh, and if you’re feeling **extra bold**, there’s a bonus challenge waiting for you! 😈

---

## 🗂️ The Files

Here’s what you have to work with:
- `jumbled_audio_1.wav`
- `jumbled_audio_2.wav`
- `jumbled_audio_3.wav`
- ...

Each file contains part of the **classified flag**, but they’re out of order! Can you restore order to the chaos? 😬

---

## 🛠️ Tools You’ll Need

To crack this challenge, you can use the following tools:
- **AudioSeal Library** 🦭: The state-of-the-art watermark detection tool.
- **Python** 🐍: For decoding the extracted fragments and reconstructing the flag.

---

## 🔍 Your Mission

1. **Detect the Watermarks** 🕵️:
   - Use the AudioSeal library to extract the **binary fragments** hidden in each audio file.
   
2. **Reorder the Fragments** 🔄:
   - Analyze the extracted binary fragments and determine their correct order to reconstruct the flag.

3. **Decode the Flag** 🔓:
   - Combine the fragments in the correct order and convert the binary back to plaintext to reveal the flag.

---

## 💣 **Bonus Challenge**: Break the AudioSeal Model!

Are you ready to go beyond and test the limits of AudioSeal? 🔥 Here’s your bonus mission:

1. **Perform an Audio Attack**:
   - Apply any audio attack (e.g., adding noise, applying filters, compressing the files).
   - **Rules**:
     - You cannot trim or alter the length of any file.
     - The order of files must remain the same as decoded flag order.

2. **Extract the Disturbed Flag**:
   - After the attack, extract the **disturbed watermark** from each file.

3. **Reconstruct the Disturbed Flag**:
   - Combine the disturbed fragments in the correct order to reconstruct the **disturbed version of the flag**.

4. **Submit Both Flags**:
   - Submit:
     1. The **original reconstructed flag** with the audiofiles correct order.
     2. The **disturbed reconstructed flag** and the code for the attack you use.

---

## 💡 Hints

### For the Main Mission:
- The flag format is: `MLH{...}`. Look for fragments that match the start (`MLH{`) and the end (`}`) of the flag to help determine the order. 🧠

### For the Bonus Challenge:
- Examples of some attacks:
  - Adding white or pink noise.
  - Lowpass or highpass filters.
  - Dynamic range compression.
- Remember: AudioSeal is **state-of-the-art**, so this won’t be easy! 😏

---

## ⚠️ Rules of Engagement ⚠️

- 📂 Do not alter the original audio files’ length or structure! Only apply attacks or extraction methods.
- 🤔 Think creatively! The files are jumbled, and the order is not obvious.
- 🏆 Submit the original and disturbed flags to maximize your score.

---

## 🎯 Submission

Once you’ve cracked the code, submit:
1. The **original reconstructed flag** with the audiofiles correct order.
2. The **disturbed reconstructed flag** and the code for the attack you use(for the bonus).

---

## 🏁 Start Now!

Are you ready to embark on this sonic adventure and uncover the hidden secrets of AudioSeal? 🎧✨

Good luck, agent. The fate of this mission rests in your hands. 🎵🔐
