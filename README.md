/* ಇಡೀ ಪೇಜ್ ಯಾವುದೇ ಸ್ಕ್ರೀನ್‌ನಲ್ಲೂ ಹೈಡ್ ಆಗದಂತೆ ತಡೆಯುವ ಕೋಡ್ */
html, body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: auto !important; /* ಇದು ಜಿಲ್ಲೆಗಳು ಕಟ್ ಆಗುವುದನ್ನು ತಡೆಯುತ್ತದೆ */
    min-height: 100vh;
    overflow-y: auto !important; /* ಇದು ಮೊಬೈಲ್‌ನಲ್ಲಿ ಕೆಳಗೆ ಸ್ಕ್ರಾಲ್ ಮಾಡಲು ಸಹಾಯ ಮಾಡುತ್ತದೆ */
    background-color: #0b132b; /* ನಿಮ್ಮ ವೆಬ್‌ಸೈಟ್‌ನ ಕಡು ನೀಲಿ ಬ್ಯಾಕ್‌ಗ್ರೌಂಡ್ ಬಣ್ಣ */
    font-family: sans-serif;
    color: white;
}

/* ಮೊಬೈಲ್ ಮತ್ತು ಡೆಸ್ಕ್‌ಟಾಪ್‌ಗೆ ಹೊಂದಿಕೊಳ್ಳುವ ರೆಸ್ಪಾನ್ಸಿವ್ ಲೇಔಟ್ */
.container, main, body {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    padding: 20px;
    box-sizing: border-box;
}

/* ನಿಮ್ಮ ಜಿಲ್ಲೆಯ ನೀಲಿ ಬಾಕ್ಸ್‌ಗಳ ಡಿಸೈನ್ */
.card, .district-box, div {
    max-width: 500px;
    width: 90%;
}
