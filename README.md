# PoetTypewriter - Multithreaded Poetry Animation

**Live typewriter effect** with parallel cursor animation.

## Code Structure
3 Classes:
├── Typewriter (extends Thread) - 100ms per character
├── CursorBlinker (extends Thread) - 300ms spaces
└── PoetTypewriter (main) - launches both threads

text

## How It Works
- **Typewriter thread**: Prints poem char-by-char (100ms delay)
- **Cursor thread**: Prints spaces simultaneously (300ms delay)  
- **Interleaved output** creates live typing effect
