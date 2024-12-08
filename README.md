# Firebase Database Reference Accessed Before Initialization

This repository demonstrates a common error in Firebase: accessing a database reference before it has fully initialized.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides the corrected version.

The error typically manifests as an unexpected behavior or a runtime error indicating that the database reference is undefined or unavailable.

**Steps to Reproduce:**
1. Clone the repository.
2. Run `bug.js`.  Observe the error.
3. Run `bugSolution.js`. Observe the correct behavior.

**Resolution:** Ensure that all database operations occur after the Firebase app has fully initialized using an appropriate callback or promise.