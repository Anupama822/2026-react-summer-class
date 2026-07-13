# React Flashcard App - TODO

## Objective

Build a Flashcard App where users can click a card to reveal the answer. Clicking the same card again should hide the answer.

---

## Requirements

### Part 1 - Display Flashcards

* [ ] Create a `flashcards` array.
* [ ] Each flashcard should contain:

  * `id`
  * `question`
  * `answer`
* [ ] Display all flashcards using `map()`.
* [ ] Give each card a unique `key`.

---

### Part 2 - State Management

* [ ] Create a state variable called `selectedId`.
* [ ] Initially, no card should be selected.

---

### Part 3 - Toggle Card

When a user clicks a card:

* [ ] If it is not selected, show the answer.
* [ ] If it is already selected, hide the answer.
* [ ] Only one card should be open at a time.

---

### Part 4 - Conditional Rendering

* [ ] Show the **question** when the card is closed.
* [ ] Show the **answer** when the card is open.

---

### Part 5 - Dynamic Classes

* [ ] Add an `active` class to the selected card.
* [ ] Change the background color of the selected card.

---

##CSS Classes

.container      /* Holds all flashcards */

.card           /* Individual flashcard */

.active         /* Applied to selected card */

---

## Concepts Practiced

* Components
* JSX
* useState
* map()
* Event Handling
* Conditional Rendering
* Dynamic className
* CSS Styling
