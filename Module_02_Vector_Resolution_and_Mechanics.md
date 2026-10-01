# পদার্থবিজ্ঞান ১ম পত্র — অধ্যায় ২: ভেক্টর | মডিউল ০২: ভেক্টরের উপাংশ বিভাজন, লম্বাংশের উপপাদ্য ও মেকানিক্স

---

## ১. ভেক্টরের বিভাজন ও উপাংশের মূল ধারণা

### ১.১ বাস্তব জীবনের উদাহরণ (ট্রলি ব্যাগের মেকানিক্স)
তুমি যখন স্টেশনে একটি ভারী চাকাযুক্ত ট্রলি ব্যাগ টেনে নিয়ে যাও, তখন হ্যান্ডেল ধরে কোণাকুণি (তির্যকভাবে) ওপরের দিকে বল $F$ প্রয়োগ করো। কিন্তু ব্যাগটি শূন্যে উড়ে যায় না, বরং মাটির সমান্তরালে সোজা সামনে এগিয়ে যায়।

এখানে তোমার প্রযুক্ত একক তির্যক বলটি ভেতরে ভেতরে একই সাথে দুটি স্বতন্ত্র কাজের জন্ম দেয়:
1. বলের একটি অংশ ব্যাগকে মাটির সমান্তরালে সোজা সামনে টেনে নিয়ে যায় (**অনুভূমিক উপাংশ**)।
2. বলের আরেকটি অংশ ব্যাগকে ওপরের দিকে তুলে মাটি থেকে কিছুটা হালকা করে (**উলম্ব উপাংশ**)।

<div class="diagram-box">
<svg viewBox="0 0 460 180" class="physics-diagram">
<defs>
<marker id="bg-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="bg-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="bg-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
<marker id="bg-arr-mu" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#78716c"/></marker>
</defs>
<line x1="30" y1="130" x2="430" y2="130" stroke="var(--text-dim)" stroke-width="1.8"/>
<circle cx="150" cy="130" r="5" fill="var(--text-main)"/>
<text x="80" y="155" fill="var(--text-main)" font-weight="700" font-size="12">ট্রলি ব্যাগ (O)</text>
<line x1="150" y1="130" x2="310" y2="35" stroke="#e11d48" stroke-width="3.5" marker-end="url(#bg-arr-rb)"/>
<text x="320" y="30" fill="#e11d48" font-weight="800" font-size="14">F (প্রযুক্ত টান বল)</text>
<line x1="150" y1="130" x2="310" y2="130" stroke="#0d9488" stroke-width="3" marker-end="url(#bg-arr-tl)"/>
<text x="210" y="152" fill="#0d9488" font-weight="700" font-size="13">Fx = F cos θ (সামনে এগিয়ে নেওয়ার বল)</text>
<line x1="150" y1="130" x2="150" y2="40" stroke="#d97706" stroke-width="3" marker-end="url(#bg-arr-amb)"/>
<text x="45" y="55" fill="#d97706" font-weight="700" font-size="13">Fy = F sin θ (ওপরে তোলার বল)</text>
<line x1="310" y1="35" x2="310" y2="130" stroke="var(--border-subtle)" stroke-width="1.5" stroke-dasharray="3,3"/>
<line x1="150" y1="35" x2="310" y2="35" stroke="var(--border-subtle)" stroke-width="1.5" stroke-dasharray="3,3"/>
<path d="M 210 130 A 60 60 0 0 0 198 102" fill="none" stroke="#e11d48" stroke-width="2"/>
<text x="215" y="115" fill="#e11d48" font-weight="800" font-size="13">θ</text>
</svg>
<div class="diagram-caption">চিত্র ১.১: ট্রলি ব্যাগের ওপর তির্যক টানের অনুভূমিক ও উল্লম্ব উপাংশ বিভাজন</div>
</div>

- **ভেক্টরের বিভাজন (Resolution of Vectors):** একটি ভেক্টর রাশিকে দুই বা ততোধিক রাশিতে বিভক্ত করার প্রক্রিয়াকে ভেক্টরের বিভাজন বলে।
- **উপাংশ (Components):** বিভক্ত অংশগুলোর প্রত্যেকটিকে মূল ভেক্টরের উপাংশ বলা হয়।

---

## ২. যেকোনো কোণে ভেক্টর বিভাজন (Non-orthogonal Resolution)

যখন কোনো ভেক্টরকে এমন দুটি দিকে বিভক্ত করতে হয় যা পরস্পর সমকোণে ($90^\circ$) নেই।

<div class="diagram-box">
<svg viewBox="0 0 520 250" class="physics-diagram">
<defs>
<marker id="no-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="no-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="no-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<line x1="60" y1="200" x2="440" y2="200" stroke="#d97706" stroke-width="3" marker-end="url(#no-arr-amb)"/>
<text x="240" y="225" fill="#d97706" font-weight="800" font-size="14">X-দিক (১ম উপাংশ: X = OA)</text>
<line x1="60" y1="200" x2="220" y2="40" stroke="#0d9488" stroke-width="3" marker-end="url(#no-arr-tl)"/>
<text x="110" y="90" fill="#0d9488" font-weight="800" font-size="14">Y-দিক (২য় উপাংশ: Y = OB)</text>
<line x1="60" y1="200" x2="380" y2="70" stroke="#e11d48" stroke-width="3.5" marker-end="url(#no-arr-rb)"/>
<text x="390" y="70" fill="#e11d48" font-weight="800" font-size="15">R⃗ = মূল ভেক্টর (OC)</text>
<line x1="220" y1="40" x2="380" y2="70" stroke="var(--border-subtle)" stroke-width="1.8" stroke-dasharray="4,4"/>
<line x1="440" y1="200" x2="380" y2="70" stroke="#0d9488" stroke-width="2" stroke-dasharray="4,4"/>
<circle cx="60" cy="200" r="4.5" fill="var(--text-main)"/>
<text x="45" y="215" fill="var(--text-main)" font-weight="800" font-size="14">O</text>
<circle cx="380" cy="70" r="4.5" fill="#e11d48"/>
<text x="375" y="55" fill="#e11d48" font-weight="800" font-size="14">C</text>
<circle cx="300" cy="200" r="4" fill="var(--text-main)"/>
<text x="295" y="220" fill="var(--text-main)" font-weight="700" font-size="13">A</text>
<path d="M 130 200 A 70 70 0 0 0 120 170" fill="none" stroke="#e11d48" stroke-width="2"/>
<text x="135" y="190" fill="#e11d48" font-weight="800" font-size="13">α</text>
<path d="M 105 155 A 70 70 0 0 0 135 150" fill="none" stroke="#0d9488" stroke-width="2"/>
<text x="110" y="135" fill="#0d9488" font-weight="800" font-size="13">β</text>
</svg>
<div class="diagram-caption">চিত্র ২.১: যেকোনো কোণে ভেক্টর বিভাজন (Non-orthogonal Resolution with Sine Rule)</div>
</div>

### ২.১ কোণের পরিচয়
- মূল ভেক্টর = $\vec{R}$
- ১ম উপাংশ = $\vec{X}$, যা মূল ভেক্টর $\vec{R}$-এর সাথে $\alpha$ কোণে ক্রিয়ারত।
- ২য় উপাংশ = $\vec{Y}$, যা মূল ভেক্টর $\vec{R}$-এর সাথে $\beta$ কোণে ক্রিয়ারত।
- $X$ ও $Y$ উপাংশদ্বয়ের মধ্যবর্তী মোট কোণ $= (\alpha + \beta)$।

### ২.২ সাইন সূত্র (Sine Rule) দিয়ে গাণিতিক প্রমাণ
ত্রিভুজ সূত্রানুসারে $\vec{X}$ এবং $\vec{Y}$ উপাংশদ্বয়ের ভেক্টর যোগফল $\vec{R}$। অতএব, $X$, $Y$ এবং $R$ বাহু তিনটি দ্বারা একটি ত্রিভুজ $\triangle OAC$ গঠিত হয়, যার তিনটি কোণ:
- $\angle AOC = \alpha$ ($Y$ বাহুর বিপরীত কোণ)
- $\angle ACO = \beta$ ($X$ বাহুর বিপরীত কোণ)
- $\angle OAC = 180^\circ - (\alpha + \beta)$ ($R$ বাহুর বিপরীত কোণ)

ত্রিকোণমিতির সাইন সূত্র অনুযায়ী:
$$\frac{\text{বাহুর দৈর্ঘ্য}}{\text{বিপরীত কোণের সাইন}} = \text{ধ্রুবক}$$
$$\frac{X}{\sin\beta} = \frac{Y}{\sin\alpha} = \frac{R}{\sin(180^\circ - (\alpha + \beta))} = \frac{R}{\sin(\alpha + \beta)}$$

অতএব, উপাংশদ্বয়ের মান:
$$\mathbf{X = \frac{R\sin\beta}{\sin(\alpha + \beta)}}$$
$$\mathbf{Y = \frac{R\sin\alpha}{\sin(\alpha + \beta)}}$$

> **মনে রাখার কৌশল:**
> $X$ উপাংশ নির্ণয়ের সময় লবে বিপরীত দিকের কোণ ($\beta$)-এর সাইন বসে।
> $Y$ উপাংশ নির্ণয়ের সময় লবে বিপরীত দিকের কোণ ($\alpha$)-এর সাইন বসে।
> এবং হরে সর্বদা উভয় কোণের সমষ্টির সাইন $\sin(\alpha + \beta)$ থাকে।

---

## ৩. পরস্পর লম্ব উপাংশে বিভাজন (Orthogonal Resolution)

<div class="diagram-box">
<svg viewBox="0 0 460 220" class="physics-diagram">
<defs>
<marker id="or-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="or-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="or-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
<marker id="or-arr-mu" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#78716c"/></marker>
</defs>
<line x1="50" y1="180" x2="420" y2="180" stroke="var(--text-main)" stroke-width="2" marker-end="url(#or-arr-mu)"/>
<text x="430" y="185" fill="var(--text-main)" font-weight="700" font-size="14">X</text>
<line x1="50" y1="180" x2="50" y2="25" stroke="var(--text-main)" stroke-width="2" marker-end="url(#or-arr-mu)"/>
<text x="45" y="15" fill="var(--text-main)" font-weight="700" font-size="14">Y</text>
<circle cx="50" cy="180" r="4.5" fill="var(--text-main)"/>
<text x="35" y="195" fill="var(--text-main)" font-weight="700" font-size="13">O</text>
<line x1="50" y1="180" x2="330" y2="50" stroke="#e11d48" stroke-width="3.5" marker-end="url(#or-arr-rb)"/>
<circle cx="330" cy="50" r="5" fill="#e11d48"/>
<text x="340" y="45" fill="#e11d48" font-weight="800" font-size="15">C(x, y) → R⃗</text>
<line x1="50" y1="180" x2="330" y2="180" stroke="#d97706" stroke-width="3.5" marker-end="url(#or-arr-amb)"/>
<text x="140" y="205" fill="#d97706" font-weight="800" font-size="13">X = R cos α (সন্নিহিত অক্ষ)</text>
<line x1="50" y1="180" x2="50" y2="50" stroke="#0d9488" stroke-width="3.5" marker-end="url(#or-arr-tl)"/>
<text x="60" y="90" fill="#0d9488" font-weight="800" font-size="13">Y = R sin α</text>
<line x1="330" y1="50" x2="330" y2="180" stroke="#0d9488" stroke-width="2" stroke-dasharray="4,4"/>
<text x="340" y="125" fill="#0d9488" font-weight="700" font-size="12">Y = R sin α</text>
<line x1="50" y1="50" x2="330" y2="50" stroke="#d97706" stroke-width="1.8" stroke-dasharray="4,4"/>
<path d="M 120 180 A 70 70 0 0 0 110 152" fill="none" stroke="#e11d48" stroke-width="2"/>
<text x="125" y="168" fill="#e11d48" font-weight="800" font-size="13">α</text>
</svg>
<div class="diagram-caption">চিত্র ৩.১: পরস্পর লম্ব উপাংশে ভেক্টর বিভাজন (Orthogonal Resolution)</div>
</div>

### ৩.১ সূত্র প্রতিপাদন
যখন দুটি উপাংশ পরস্পর সমকোণে ($90^\circ$) থাকে, তখন $\alpha + \beta = 90^\circ \implies \beta = 90^\circ - \alpha$।
সাধারণ সূত্রে মান বসিয়ে:
$$X = \frac{R\sin(90^\circ - \alpha)}{\sin 90^\circ} = \frac{R\cos\alpha}{1} = \mathbf{R\cos\alpha}$$
$$Y = \frac{R\sin\alpha}{\sin 90^\circ} = \frac{R\sin\alpha}{1} = \mathbf{R\sin\alpha}$$

### ৩.২ 🔑 সোনালি মাস্টার রুল
> **"কোণ ($\theta$) যে অক্ষের সাথে যুক্ত থাকবে, সেদিকে উপাংশ হবে $\cos\theta$; এবং তার লম্ব দিকে উপাংশ হবে $\sin\theta$।"**

| কোণ কার সাথে দেওয়া আছে | অনুভূমিক উপাংশ ($F_x$) | উলম্ব উপাংশ ($F_y$) |
| :--- | :---: | :---: |
| **অনুভূমিকের সাথে $\theta$ কোণ** | $\mathbf{F\cos\theta}$ | $\mathbf{F\sin\theta}$ |
| **উলম্বের সাথে $\theta$ কোণ (ট্র্যাপ!)** | $\mathbf{F\sin\theta}$ | $\mathbf{F\cos\theta}$ |

---

## ৪. উপাংশের বাস্তব প্রয়োগ ও গতিবিজ্ঞান (Real-World Applications)

### 🚜 ৪.১ লন রোলার — টানা সহজ কিন্তু ঠেলা কঠিন কেন?
রোলারের ভর $m$, তাই তার প্রকৃত ওজন $W = mg$ সর্বদা খাড়া নিচের দিকে ক্রিয়া করে।

<div class="diagram-box">
<svg viewBox="0 0 500 220" class="physics-diagram">
<defs>
<marker id="bt-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="bt-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="bt-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<line x1="20" y1="40" x2="480" y2="40" stroke="#0284c7" stroke-width="3"/>
<rect x="20" y="40" width="460" height="150" fill="rgba(2, 132, 199, 0.05)"/>
<text x="30" y="30" fill="#0284c7" font-weight="700" font-size="13">নদীর তীর (Bank)</text>
<line x1="160" y1="40" x2="320" y2="130" stroke="#d97706" stroke-width="2.5" stroke-dasharray="3,2"/>
<text x="210" y="70" fill="#d97706" font-weight="800" font-size="13">গুণ বা দড়ির টান বল F</text>
<ellipse cx="320" cy="130" rx="36" ry="16" fill="rgba(217, 119, 6, 0.2)" stroke="#d97706" stroke-width="2.5"/>
<circle cx="320" cy="130" r="4" fill="var(--text-main)"/>
<text x="365" y="135" fill="var(--text-main)" font-weight="700" font-size="13">নৌকা</text>
<line x1="320" y1="130" x2="440" y2="130" stroke="#0d9488" stroke-width="3" marker-end="url(#bt-arr-tl)"/>
<text x="340" y="160" fill="#0d9488" font-weight="700" font-size="12">Fx = F cos θ (সামনে এগিয়ে নেওয়ার কার্যকর বল)</text>
<line x1="320" y1="130" x2="320" y2="60" stroke="#e11d48" stroke-width="2.5" marker-end="url(#bt-arr-rb)"/>
<text x="325" y="80" fill="#e11d48" font-weight="700" font-size="11">Fy = F sin θ (তীরের দিকে টানে - যা হাল দিয়ে প্রতিহত করা হয়)</text>
<path d="M 270 102 A 40 40 0 0 0 290 130" fill="none" stroke="#d97706" stroke-width="2"/>
<text x="260" y="125" fill="#d97706" font-weight="800" font-size="13">θ</text>
</svg>
<div class="diagram-caption">চিত্র ৪.১: নৌকার গুণ টানা (Towing of Boat) ও বলের উপাংশ বিভাজন</div>
</div>

- **অনুভূমিক উপাংশ ($F_x = F\cos\theta$):** নৌকাকে নদীর দৈর্ঘ্য বরাবর সোজা সামনের দিকে এগিয়ে নিয়ে যায়।
- **উলম্ব উপাংশ ($F_y = F\sin\theta$):** নৌকাকে তীরের দিকে আছড়ে ফেলতে চায়। মাঝিরা হালের সাহায্যে এই উপাংশকে নিষ্ক্রিয় (Cancel) করেন।
- **দড়ি যত লম্বা করা হয়, নৌকা টানা তত সহজ হয় কেন?**
  - দড়ির দৈর্ঘ্য বৃদ্ধি পেলে তীরের সাথে দড়ির কোণ $\theta$ ছোট হয় ($	heta \downarrow$)।
  - কোণ $\theta$ কমলে $\cos\theta$-র মান বৃদ্ধি পায় ($\cos\theta \uparrow$), ফলে সামনে এগিয়ে নেওয়ার কার্যকর বল $\mathbf{F\cos\theta}$ বৃদ্ধি পায়।
  - একই সাথে ক্ষতিকর উপাংশ $F\sin\theta$ হ্রাস পায়।
  - তাই দড়ি যত লম্বা হবে, গুণ টেনে নৌকা চালানো তত দ্রুত ও সহজ হবে।

---

### 🕊️ ৪.৩ পাখির ডানা ঝাপটানো ও আকাশে ওড়া
পাখি যখন আকাশে ওড়ে, তখন তার দুটি ডানা দিয়ে বায়ুর ওপর তির্যকভাবে পেছনের দিকে বল $F_1$ ও $F_2$ প্রয়োগ করে।
- নিউটনের ৩য় সূত্রানুসারে বায়ু পাখির ডানার ওপর সমান ও বিপরীতমুখী প্রতিক্রিয়া বল $R_1$ ও $R_2$ প্রয়োগ করে।
- প্রতিক্রিয়া বলগুলোর উলম্ব উপাংশ $R\sin\theta$ পাখির ওজনকে প্রশমিত করে আকাশে ভাসিয়ে রাখে।
- প্রতিক্রিয়া বলগুলোর অনুভূমিক উপাংশ $2R\cos\theta$ পাখিকে দ্রুত সামনের দিকে উড়ে যেতে সাহায্য করে।

---

## ৫. লম্বাংশের উপপাদ্য (Law of Components)

### ৫.১ বিবৃতি
> যেকোনো নির্দিষ্ট দিক বরাবর সমতলীয় কতগুলো ভেক্টরের উপাংশের বীজগণিতীয় যোগফল, ওই নির্দিষ্ট দিক বরাবর এদের লব্ধির উপাংশের সমান।

### ৫.২ গাণিতিক সমাধানের ৪টি ধাপ
ধরা যাক, $F_1, F_2, F_3, \dots$ বলসমূহ $X$-অক্ষের সাথে যথাক্রমে $\theta_1, \theta_2, \theta_3, \dots$ কোণে ক্রিয়ারত।
1. **$X$-অক্ষ বরাবর মোট উপাংশ:**
   $$R_x = \sum F_x = F_1\cos\theta_1 + F_2\cos\theta_2 + F_3\cos\theta_3 + \dots$$
2. **$Y$-অক্ষ বরাবর মোট উপাংশ:**
   $$R_y = \sum F_y = F_1\sin\theta_1 + F_2\sin\theta_2 + F_3\sin\theta_3 + \dots$$
3. **একক লব্ধির মান ($R$):**
   $$\mathbf{R = \sqrt{R_x^2 + R_y^2}}$$
4. **লব্ধির দিক ($\theta$):**
   $$\mathbf{\theta = \tan^{-1}\left(\frac{R_y}{R_x}\right)}$$

---

## ৬. ল্যামির উপপাদ্য (Lami's Theorem)

<div class="diagram-box">
<svg viewBox="0 0 440 250" class="physics-diagram">
<defs>
<marker id="lm-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="lm-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="lm-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<circle cx="220" cy="130" r="5" fill="var(--text-main)"/>
<text x="205" y="150" fill="var(--text-main)" font-weight="800" font-size="14">O</text>
<line x1="220" y1="130" x2="220" y2="30" stroke="#e11d48" stroke-width="3.5" marker-end="url(#lm-arr-rb)"/>
<text x="228" y="25" fill="#e11d48" font-weight="800" font-size="16">P⃗ (বল ১)</text>
<line x1="220" y1="130" x2="100" y2="210" stroke="#d97706" stroke-width="3.5" marker-end="url(#lm-arr-amb)"/>
<text x="65" y="225" fill="#d97706" font-weight="800" font-size="16">Q⃗ (বল ২)</text>
<line x1="220" y1="130" x2="350" y2="190" stroke="#0d9488" stroke-width="3.5" marker-end="url(#lm-arr-tl)"/>
<text x="360" y="200" fill="#0d9488" font-weight="800" font-size="16">R⃗ (বল ৩)</text>
<path d="M 165 165 A 60 60 0 0 0 275 160" fill="none" stroke="#e11d48" stroke-width="2.2"/>
<text x="210" y="190" fill="#e11d48" font-weight="800" font-size="14">α (P-এর বিপরীত কোণ)</text>
<path d="M 220 80 A 50 50 0 0 0 180 100" fill="none" stroke="#0d9488" stroke-width="2"/>
<text x="165" y="75" fill="#0d9488" font-weight="800" font-size="14">β (R-এর বিপরীত কোণ)</text>
<path d="M 260 90 A 50 50 0 0 0 220 80" fill="none" stroke="#d97706" stroke-width="2"/>
<text x="260" y="80" fill="#d97706" font-weight="800" font-size="14">γ (Q-এর বিপরীত কোণ)</text>
</svg>
<div class="diagram-caption">চিত্র ৫.১: ল্যামির উপপাদ্য ও তিনটি বলের সাম্যাবস্থা ($rac{P}{\sinlpha} = rac{Q}{\sineta} = rac{R}{\sin\gamma}$)</div>
</div>

### ৬.১ উপপাদ্যের বিবৃতি
> কোনো বিন্দুতে একই সমতলে ক্রিয়ারত তিনটি ভেক্টর বল যদি বস্তুকে সাম্যাবস্থায় (Equilibrium) রাখে, তবে প্রতিটি বলের মান অপর দুটি বলের মধ্যবর্তী কোণের সাইনের (Sine) সমানুপাতিক।

### ৬.২ গাণিতিক সমীকরণ
$$\mathbf{\frac{P}{\sin\alpha} = \frac{Q}{\sin\beta} = \frac{R}{\sin\gamma}}$$
- $P$-এর বিপরীত কোণ = $Q$ ও $R$-এর মধ্যবর্তী কোণ ($\alpha$)
- $Q$-এর বিপরীত কোণ = $P$ ও $R$-এর মধ্যবর্তী কোণ ($\beta$)
- $R$-এর বিপরীত কোণ = $P$ ও $Q$-এর মধ্যবর্তী কোণ ($\gamma$)

---

## ৭. সমাধানকৃত গাণিতিক সমস্যা ও বোর্ড সিকিউ (Worked CQ Problems)

### 📌 সমস্যা ১: লন রোলার বোর্ড সিকিউ (উলম্ব কোণ ট্র্যাপ)
**প্রশ্ন:** $15\text{ kg}$ ভরের একটি লন রোলারকে উলম্বের সাথে $30^\circ$ কোণে $98\text{ N}$ বল প্রয়োগ করে একজন মালী প্রথমে ঠেললেন এবং পরে একই বলে টানলেন ($g = 9.8\text{ m/s}^2$)।
(গ) লন রোলারটিকে টানার সময় এর আপাত ওজন কত হবে?
(ঘ) মালী রোলারটিকে ঠেলার বদলে টেনে নেওয়া সুবিধাজনক মনে করলেন কেন?—গাণিতিকভাবে বিশ্লেষণ করো।

**সমাধান:**
- **প্রদত্ত মান:** $m = 15\text{ kg}$, $W = mg = 15 \times 9.8 = 147\text{ N}$, $F = 98\text{ N}$, উলম্বের সাথে কোণ $\theta = 30^\circ$
- **(গ) টানার সময় আপাত ওজন:**
  যেহেতু কোণ উলম্বের সাথে, উলম্ব উপাংশ $= F\cos 30^\circ = 98 \times 0.866 = 84.87\text{ N}$
  $$W_{pull} = W - F\cos 30^\circ = 147 - 84.87 = \mathbf{62.13\text{ N}}$$
- **(ঘ) ঠেলার সময় আপাত ওজন ও তুলনা:**
  $$W_{push} = W + F\cos 30^\circ = 147 + 84.87 = \mathbf{231.87\text{ N}}$$
  সামনে নেওয়ার বল উভয় ক্ষেত্রে সমান ($F_x = F\sin 30^\circ = 49\text{ N}$)।
  আপাত ওজনের পার্থক্য $\Delta W = 231.87 - 62.13 = \mathbf{169.74\text{ N}}$।
  ঠেলার সময় মেঝেতে চাপ $169.74\text{ N}$ বেশি হওয়ায় ঘর্ষণ বল মারাত্মক বৃদ্ধি পায়, ফলে ঠেলে নেওয়া কঠিন কিন্তু টেনে নেওয়া সুবিধাজনক।

---

### 📌 সমস্যা ২: লম্বাংশের উপপাদ্যে বহু-বলের লব্ধি
**প্রশ্ন:** একটি বিন্দুতে তিনটি বল ক্রিয়ারত: $F_1 = 10\text{ N}$ ($0^\circ$), $F_2 = 20\text{ N}$ ($60^\circ$), $F_3 = 15\text{ N}$ ($120^\circ$)। লব্ধির মান ও দিক নির্ণয় করো।

**সমাধান:**
- $R_x = 10\cos 0^\circ + 20\cos 60^\circ + 15\cos 120^\circ = 10(1) + 20(0.5) + 15(-0.5) = \mathbf{12.5\text{ N}}$
- $R_y = 10\sin 0^\circ + 20\sin 60^\circ + 15\sin 120^\circ = 0 + 20(0.866) + 15(0.866) = \mathbf{30.31\text{ N}}$
- লব্ধির মান: $R = \sqrt{(12.5)^2 + (30.31)^2} = \sqrt{156.25 + 918.70} = \sqrt{1074.95} \approx \mathbf{32.78\text{ N}}$
- লব্ধির দিক: $\theta = \tan^{-1}\left(\frac{30.31}{12.5}\right) = \tan^{-1}(2.4248) \approx \mathbf{67.58^\circ}$

---

## ৫. স্ব-মূল্যায়ন ও প্র্যাকটিস চ্যালেঞ্জ (Mechanics Practice Problems)

<div class="practice-card">
<div class="practice-header">
<span class="practice-badge">প্র্যাকটিস ০১</span>
<h4>লন রোলারের ঠেলা বনাম টানার ওজন পার্থক্য</h4>
</div>
  <p><strong>প্রশ্ন:</strong> $20\text{ kg}$ ভরের একটি লন রোলারকে অণুভূমিকের সাথে $30^\circ$ কোণে $50\text{ N}$ বল প্রয়োগ করে ঠেলা হলো এবং একই বলে টানা হলো।</p>
  <ol>
    <li>ঠেলা ও টানার ক্ষেত্রে রোলারের কার্যকর ওজন কত হবে? ($g = 9.8\text{ ms}^{-2}$)</li>
    <li>উভয় ক্ষেত্রে কার্যকর ওজনের পার্থক্য কত?</li>
  </ol>
<details class="practice-collapse">
<summary class="practice-summary">💡 সমাধান ও উত্তর দেখতে ক্লিক করুন</summary>
<div class="practice-solution">
<p><strong>সমাধান:</strong></p>
<p>প্রকৃত ওজন $W = mg = 20 \times 9.8 = 196\text{ N}$</p>
<p>উল্লম্ব উপাংশ $F\sin\theta = 50\sin 30^\circ = 50 \times 0.5 = 25\text{ N}$</p>
<ul>
<li><strong>ঠেলার ক্ষেত্রে ওজন:</strong> $W_{push} = W + F\sin\theta = 196 + 25 = \mathbf{221\text{ N}}$</li>
<li><strong>টানার ক্ষেত্রে ওজন:</strong> $W_{pull} = W - F\sin\theta = 196 - 25 = \mathbf{171\text{ N}}$</li>
<li><strong>ওজনের পার্থক্য:</strong> $\Delta W = 2F\sin\theta = 2(25) = \mathbf{50\text{ N}}$ (উত্তর)</li>
</ul>
</div>
  </details>
</div>

<div class="practice-card">
<div class="practice-header">
<span class="practice-badge">প্র্যাকটিস ০২</span>
<h4>ল্যামির উপপাদ্যের সাম্যাবস্থা প্রয়োগ</h4>
</div>
  <p><strong>প্রশ্ন:</strong> একটি বিন্দুতে তিনটি বল $P, Q, R$ সাম্যাবস্থায় রয়েছে। $P$ ও $Q$-এর মধ্যবর্তী কোণ $120^\circ$ এবং $Q$ ও $R$-এর মধ্যবর্তী কোণ $150^\circ$। বলত্রয়ের মানের অনুপাত $P : Q : R$ কত?</p>
<details class="practice-collapse">
<summary class="practice-summary">💡 সমাধান ও উত্তর দেখতে ক্লিক করুন</summary>
<div class="practice-solution">
<p><strong>সমাধান:</strong></p>
<p>৩য় কোণ ( $P$ ও $R$-এর মধ্যবর্তী কোণ) $= 360^\circ - (120^\circ + 150^\circ) = 360^\circ - 270^\circ = 90^\circ$</p>
<p>ল্যামির উপপাদ্য অনুসারে:</p>
      $$\frac{P}{\sin 150^\circ} = \frac{Q}{\sin 90^\circ} = \frac{R}{\sin 120^\circ}$$
      $$\frac{P}{0.5} = \frac{Q}{1} = \frac{R}{\frac{\sqrt{3}}{2}} \implies P : Q : R = 0.5 : 1 : 0.866 = \mathbf{1 : 2 : \sqrt{3}}$$
</div>
  </details>
</div>
