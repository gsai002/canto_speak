# Project TODO List

## Features
- [x] **Auto-pronounce**: Automatically play the sentence audio when a new sentence is loaded.
- [ ] **Category Filtering**: Allow users to filter sentences by categories (e.g., Work, Life, Travel, Shopping).
- [ ] **Progress Tracking**: Mark sentences as "Learned" or "Mastered" and persist this state.
- [ ] **Favorites**: Allow users to "star" difficult sentences for focused practice.
- [ ] **Search**: Add a search bar to find specific sentences by text or meaning.
- [ ] **Daily Challenge**: Present a set of 5 random sentences daily for practice.

## UI/UX
- [ ] **Dark Mode**: Add a toggle for dark/light mode.
- [ ] **Mobile Responsiveness**: Optimize layout for smaller screens (adjust padding, font sizes).
- [ ] **Animations**: Add smooth transitions when switching sentences or showing feedback.
- [ ] **Loading States**: Show a loading spinner or skeleton while audio is generating/fetching.
- [ ] **Keyboard Shortcuts**: Add shortcuts for "Next Sentence" (Space/Right Arrow) and "Record" (R).

## Technical
- [ ] **PWA Support**: Make the app installable and work offline (cache assets and sentences).
- [ ] **Unit Tests**: Add tests for critical logic (scoring algorithm, sentence fetching).
- [ ] **CI/CD**: Set up a basic pipeline for linting and building on push.
- [ ] **Accessibility (a11y)**: Ensure all controls are keyboard accessible and have proper ARIA labels.
- [ ] **Error Handling**: Better handling for microphone permission denial or speech recognition errors.