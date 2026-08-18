## 2026-08-18 - Link form labels to inputs
**Learning:** Implicit or missing associations between `<label>` elements and form controls (`<input>`, `<select>`) are common accessibility pitfalls that hinder screen readers and prevent users from clicking the label to focus the input.
**Action:** Always verify that every `<label>` element includes a `for` attribute explicitly matching the `id` of its associated form control.
