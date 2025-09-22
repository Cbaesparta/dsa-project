# Music Player Using Data Structures

This project is a C++ based **Music Player**, developed as part of the **Data Structures and Algorithms**. It demonstrates the practical application of core data structures to build a functional music player with features such as playlist management, song navigation, and history tracking.

The project uses **doubly linked lists, stacks, queues, and file handling** to organize and manipulate songs efficiently.

---

## Features
- **Add / Remove Songs:** Easily manage your playlist.  
- **Play Next / Previous Song:** Navigate through the playlist using a doubly linked list.  
- **Recently Played Songs:** Keep track of song history using a stack.  
- **Upcoming Songs Queue:** Manage the queue of songs to be played next.  
- **Persistent Storage:** Save and load playlists using file handling.

---

## Data Structures Used
- **Doubly Linked List:** For playlist navigation.  
- **Stack:** To track recently played songs.  
- **Queue:** To manage upcoming songs.  
- **File Handling:** To read and write playlists to a file.

---

## Project Structure
```cpp
main.cpp            // Entry point of the program
playlist.cpp        // Playlist operations using doubly linked list
playlist.h          // Playlist header file
stack.cpp           // Recently played songs (stack implementation)
stack.h
queue.cpp           // Upcoming songs (queue implementation)
queue.h
songs.txt           // File storing song details
README.md           // Project documentation
