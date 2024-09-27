# Audio Test

This project is a simple audio test web application designed to help users practice speaking skills. The application consists of two pages: one for writing and another for voice recording. The user's answers are saved locally in the browser, allowing them to continue where they left off.

## Features

1. **Audio Recording Test (audio_test.html)**
   - Two questions prompt users to answer by recording their voices:
     1. "Tell me 4 sentences about you."
     2. "Tell in 4 sentences about your favorite trip."
   - Users can record their answers, each limited to 30 seconds, and play them back.
   - Audio recordings are handled using the Web Audio API and can be replayed on the page.

## How to Use

### Audio Recording Test (audio_test.html)
1. Open `audio_test.html` in a web browser (Chrome or Firefox recommended).
2. Click the "Start Recording (30s)" button to record your answer for each question.
3. The recording will automatically stop after 30 seconds.
4. Play back your recording using the audio controls below each question.

## Technologies Used
- **HTML**: For page structure.
- **CSS**: For basic styling.
- **JavaScript**: 
  - Uses the Web Audio API to record and play back audio responses.

## Installation and Deployment
