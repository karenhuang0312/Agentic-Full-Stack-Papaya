# User Stories Template

---

- **US-001:** As a user, I want to browse popular destinations from the homepage so that I can explore flight options quickly.

  _Expanded Context / description:_
  > Popular destinations are displayed visually on the homepage, enabling discovery for users who may not have a specific destination in mind.

  - **Acceptance Criteria:**
    - [ ] Homepage displays a list/grid of popular destinations.
    - [ ] Each destination can be clicked to start a flight search.
    - [ ] Destinations are curated based on trends or business requirements.

---

- **US-002:** As a user, I want to search for flights using a form so that I can find flights based on my travel needs.

  _Expanded Context / description:_
  > The search form allows users to input origin, destination, dates, and other basic info. No account or personal data required.

  - **Acceptance Criteria:**
    - [ ] Search form is present and functional.
    - [ ] Users can search without logging in.
    - [ ] Search results match criteria entered.

---

- **US-003:** As a user, I want to sort available flights by price and airline so that I can find the best option for my budget or preferred carrier.

  _Expanded Context / description:_
  > After searching, results can be sorted by ascending/descending price and by airline name.

  - **Acceptance Criteria:**
    - [ ] Search results offer sorting by price and airline.
    - [ ] Sorting is responsive and updates results instantly.
    - [ ] Sort options are visible and accessible.

---

- **US-004:** As a user, I want to sign up or sign in (without providing email or phone) so that I can save searches or preferences with minimal friction.

  _Expanded Context / description:_
  > Users create basic accounts using only a username and password. No email or phone is required for MVP.

  - **Acceptance Criteria:**
    - [ ] Account creation and login require only username and password.
    - [ ] No email or phone validation.
    - [ ] Users can access saved searches or preferences after login.

---

- **US-005:** As a user, when I select a flight, I want to be redirected to the airline’s official website to complete the booking.

  _Expanded Context / description:_
  > Direct booking and payment are out of scope; users will be sent to the airline’s official site for final ticket purchase.

  - **Acceptance Criteria:**
    - [ ] Each flight result provides a clear “Book” or “Go to Airline” button.
    - [ ] Redirect occurs within 2 seconds without errors.

---

- **US-006:** As a user, I want to see clear error messages and empty states when no flights match my search so that I am not confused.

  _Expanded Context / description:_
  > If a search fails, no flights are found, or an API error occurs, the UI displays helpful messages and suggestions. Example Message: "No flights found. Please try different dates or destinations."

  - **Acceptance Criteria:**
    - [ ] Empty state and error messages are shown when appropriate.
    - [ ] UI guides users to retry or change search criteria.

---
