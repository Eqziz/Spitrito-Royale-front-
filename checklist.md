# Tag Checklist — Assignment 1 (Spirito Royal Project)

* **Organization**: Spirito Royal (Barbershop & MarketBar, Astana)[cite: 1]
* **Team Members**:
  * Student 1 (Lead): Nodir Muhammedov (`services.html`, `booking.html`, `feedback.html`)[cite: 1]
  * Student 2: Yerulan Baimbet (`barbers.html`, `booking.html`, `careers.html`)[cite: 1]
  * Student 3: Nurassyl Ilyas (`marketbar.html`, `colophon.html`)[cite: 1]

---

## 1. Mandatory Page Structure & Meta Elements (Every Page)

| Element / Requirement | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| `<!DOCTYPE html>` | `index.html` | 1 | Team | Standard HTML5 declaration[cite: 1] |
| `<html lang="en">` | `index.html` | 3 | Team | Primary natural language attribute[cite: 1] |
| `<meta charset="UTF-8">` | `index.html` | 5 | Team | Document encoding declaration[cite: 1] |
| `<meta name="viewport">` | `index.html` | 6 | Team | Mobile responsiveness scale[cite: 1] |
| `<meta name="description">` | `index.html` | 7 | Team | Search snippet summary[cite: 1] |
| `<meta name="author">` | `index.html` | 8 | Team | Team authorship metadata[cite: 1] |
| `<title>` (unique) | `index.html` | 9 | Team | Unique tab identifier[cite: 1] |
| `<h1>` (exactly one) | `index.html` | 14 | Team | Topmost heading of site hierarchy[cite: 1] |
| `<header>` | `index.html` | 13 | Team | Site-wide identity header[cite: 1] |
| `<nav>` with relative links | `index.html` | 15–26 | Team | Contains full 8-page navigation list[cite: 1] |
| `<main>` | `index.html` | 29 | Team | Central unique page content[cite: 1] |
| `<footer>` | `index.html` | 64 | Team | Contacts, links, and copyright[cite: 1] |
| HTML comment (author) | `index.html` | 2 | Team | Top author attribution comment[cite: 1] |
| HTML comment 1 (why) | `index.html` | 12 | Team | Explains global nav architecture[cite: 1] |
| HTML comment 2 (why) | `index.html` | 41 | Team | Explains real quote integration[cite: 1] |

---

## 2. Semantic Document Outlining

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| `<section>` | `index.html` | 30 | Team | "About" thematic block[cite: 1] |
| `<article>` | `services.html` | 26 | Nodir M. | Self-contained price service catalog[cite: 1] |
| `<aside>` | `index.html` | 55 | Team | Guest privileges and anchor jumps[cite: 1] |
| `<figure>` | `index.html` | 46 | Team | Wraps lounge photo with caption[cite: 1] |
| `<figcaption>` | `index.html` | 48 | Team | Descriptive caption for photo1.jpg[cite: 1] |

---

## 3. Tables (Real Data with Strict Semantics)

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| `<table>` | `services.html` | 34 | Nodir M. | Master grooming rates table[cite: 1] |
| `<caption>` | `services.html` | 35 | Nodir M. | Official pricing title for 2026[cite: 1] |
| `<thead>` | `services.html` | 36 | Nodir M. | Column groupings header[cite: 1] |
| `<tbody>` | `services.html` | 44 | Nodir M. | Tabular pricing data body[cite: 1] |
| `<th scope="col">` | `services.html` | 38 | Nodir M. | Column header scope mapping[cite: 1] |
| `<th scope="row">` | `services.html` | 45 | Nodir M. | Row header scope mapping[cite: 1] |

---

## 4. Lists

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| Nested List (`<ul>` inside `<ul>`) | `barbers.html` | 51–64 | Student 2 | Master specialization hierarchy[cite: 1] |
| Ordered List with attr (`<ol type="I">`) | `barbers.html` | 44–48 | Student 2 | Chronology of Astana branches[cite: 1] |
| Definition List (`<dl>`, `<dt>`, `<dd>`) | `services.html` | 74–79 | Nodir M. | Sanitation protocol definitions[cite: 1] |

---

## 5. Hyperlinks

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| External Link (`target="_blank"`, `rel`) | `index.html` | 68 | Team | 2GIS external capital map link[cite: 1] |
| Link `mailto:` | `index.html` | 67 | Team | Contact mailbox link[cite: 1] |
| Link `tel:` | `index.html` | 66 | Team | Reception telephone dialer[cite: 1] |
| In-page id link 1 (`href="#about"`) | `index.html` | 60 | Team | Anchor jump to about section[cite: 1] |
| In-page id link 2 (`href="#philosophy"`) | `index.html` | 60 | Team | Anchor jump to philosophy section[cite: 1] |

---

## 6. Images (Real Photographs with Meaningful Alt)

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| `<img> (photo1.jpg)` | `index.html` | 47 | Team | Real photo: lounge area, tables, Edison lamps[cite: 1] |
| `<img> (photo2.jpg)` | `services.html` | 83 | Nodir M. | Real photo: cutting stations and barber chair[cite: 1] |
| `<img> (photo3.jpg)` | `barbers.html` | 73 | Student 2 | Real photo: master holding gold/black shears[cite: 1] |
| `<img> (photo4.jpg)` | `marketbar.html` | 83 | Student 3 | Real photo: MarketBar counter and glassware[cite: 1] |

---

## 7. Text Semantics, Inline Elements & Formatting

| Element | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| `<strong>` | `colophon.html` | 71 | Student 3 | Author name emphasis[cite: 1] |
| `<em>` | `colophon.html` | 27 | Student 3 | Course title emphasis[cite: 1] |
| `<b>` | `index.html` | 32 | Team | Brand styling without added stress[cite: 1] |
| `<i>` | `colophon.html` | 70 | Student 3 | Publication formatting[cite: 1] |
| `<mark>` | `index.html` | 57 | Team | 10% cashback highlighted marker[cite: 1] |
| `<small>` | `colophon.html` | 30 | Student 3 | Diagnostic disclaimer note[cite: 1] |
| `<sub>` | `booking.html` | 34 | Nodir M. | Subscript in chemical formula H₂O[cite: 1] |
| `<abbr title="...">` (1) | `colophon.html` | 27 | Student 3 | Expansion for "SRB"[cite: 1] |
| `<abbr title="...">` (2) | `colophon.html` | 27 | Student 3 | Expansion for "W3C"[cite: 1] |
| `<blockquote>` (real quote) | `index.html` | 42–44 | Team | Real quote from Master Azamat[cite: 1] |
| `<q>` | `booking.html` | 31 | Nodir M. | Inline quotation from floor manager[cite: 1] |
| `<cite>` | `colophon.html` | 70 | Student 3 | Citation of HTML5 Living Standard[cite: 1] |
| `<code>` | `colophon.html` | 61 | Student 3 | Terminal command `git status`[cite: 1] |
| `<pre>` | `colophon.html` | 51–58 | Student 3 | Preformatted HTML template block[cite: 1] |
| `<kbd>` | `colophon.html` | 64 | Student 3 | Keystroke combo `Ctrl + Shift + I`[cite: 1] |
| `<samp>` | `colophon.html` | 67 | Student 3 | Sample command-line output message[cite: 1] |
| `<hr>` | `colophon.html` | 45 | Student 3 | Thematic break rule[cite: 1] |
| `<br>` | `colophon.html` | 70 | Student 3 | Deliberate line break[cite: 1] |
| HTML Entity 1 (`&trade;`) | `index.html` | 69 | Team | Trademark symbol[cite: 1] |
| HTML Entity 2 (`&bull;`) | `index.html` | 69 | Team | Bullet divider[cite: 1] |
| HTML Entity 3 (`&sect;`) | `index.html` | 69 | Team | Section symbol[cite: 1] |
| HTML Entity 4 (`&reg;`) | `services.html` | 92 | Nodir M. | Registered trademark symbol[cite: 1] |
| HTML Entity 5 (`&copy;`) | `index.html` | 69 | Team | Copyright symbol[cite: 1] |

---

## 8. Generic Containers with Justifications

| Element | File | Line No. | Author | Justification (Why no semantic tag fits) |
| :--- | :--- | :--- | :--- | :--- |
| `<div>` | `colophon.html` | 37 | Student 3 | System status wrapper; no semantic content (neither article nor section) fits purely technical diagnostics[cite: 1]. |
| `<span>` | `colophon.html` | 42 | Student 3 | Inline stylistic hook used to isolate validation status string without altering text semantics[cite: 1]. |

---

## 9. Interactive Forms (Three Distinct Implementations)

| Required Form Feature | File | Line No. | Author | Notes / Context |
| :--- | :--- | :--- | :--- | :--- |
| **Form 1: Online Booking** | `booking.html` | 40–99 | Nodir M. | Appointment booking interface[cite: 1] |
| `method="post"`, `action="#"` | `booking.html` | 40 | Nodir M. | Form transport definition[cite: 1] |
| `<fieldset>` and `<legend>` | `booking.html` | 41, 56 | Nodir M. | Logically grouped inputs[cite: 1] |
| `<label for>` tied to `id` | `booking.html` | 43–44 | Nodir M. | Full accessible association[cite: 1] |
| `input type="text"` | `booking.html` | 44 | Nodir M. | Name input[cite: 1] |
| `input type="email"` | `booking.html` | 52 | Nodir M. | Email address input[cite: 1] |
| `input type="tel"` | `booking.html` | 48 | Nodir M. | Phone number input[cite: 1] |
| `input type="number"` | `booking.html` | 69 | Nodir M. | Guest quantity counter[cite: 1] |
| `input type="date"` | `booking.html` | 65 | Nodir M. | Appointment date picker[cite: 1] |
| Radio Group (`type="radio"`) | `booking.html` | 73–78 | Nodir M. | Master tier selector[cite: 1] |
| Checkbox (`type="checkbox"`) | `booking.html` | 86 | Nodir M. | Privacy agreement toggle[cite: 1] |
| `<select>` and `<option>` | `booking.html` | 58–63 | Nodir M. | Astana branch selector[cite: 1] |
| `<textarea>` | `booking.html` | 82 | Nodir M. | Style instructions comment box[cite: 1] |
| `required` & `placeholder` | `booking.html` | 44, 48 | Nodir M. | In-browser validation attributes[cite: 1] |
| `<button type="submit">` | `booking.html` | 91 | Nodir M. | Form submission button[cite: 1] |
| `<button type="reset">` | `booking.html` | 92 | Nodir M. | Form clear button[cite: 1] |
| Comment: No Backend | `booking.html` | 35–39 | Nodir M. | States form does not send data yet[cite: 1] |
| **Form 2: Feedback Registry** | `feedback.html` | 40–98 | Student 2 | Client QA review form (full fields)[cite: 1] |
| **Form 3: Career Application**| `careers.html` | 40–98 | Student 3 | Master job/academy signup (full fields)[cite: 1] |