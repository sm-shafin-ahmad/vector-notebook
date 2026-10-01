# পদার্থবিজ্ঞান ১ম পত্র — অধ্যায় ২: ভেক্টর | মডিউল ০১: ভেক্টরের মৌলিক ধারণা ও সামান্তরিক সূত্র

---

## ১. ভৌত রাশি ও স্কেলার বনাম ভেক্টর রাশি

### ১.১ ভৌত রাশি (Physical Quantity) কী?
ভৌত জগতে যা কিছু সরাসরি বা পরোক্ষভাবে পরিমাপ করা যায়, তাকে **ভৌত রাশি (Physical Quantity)** বলে। যেমন: কোনো বস্তুর দৈর্ঘ্য, ভর, সময়, তাপমাত্রা, বেগ, ত্বরণ, বল ইত্যাদি।

পরিমাপের বৈশিষ্ট্যের ওপর ভিত্তি করে ভৌত রাশিকে প্রধানত দুটি শ্রেণিতে ভাগ করা হয়:
1. **অদিক রাশি বা স্কেলার রাশি (Scalar Quantity)**
2. **দিক রাশি বা ভেক্টর রাশি (Vector Quantity)**

---

### ১.২ স্কেলার ও ভেক্টর রাশির গভীর তুলনামূলক বিশ্লেষণ

| বৈশিষ্ট্য | স্কেলার রাশি (Scalar Quantity) | ভেক্টর রাশি (Vector Quantity) |
| :--- | :--- | :--- |
| **সংজ্ঞা** | যে সকল ভৌত রাশিকে সম্পূর্ণরূপে প্রকাশ করার জন্য শুধুমাত্র **মান** (Magnitude)-এর প্রয়োজন হয়, কোনো দিকের প্রয়োজন হয় না। | যে সকল ভৌত রাশিকে সম্পূর্ণরূপে প্রকাশ করার জন্য **মান ও দিক** (Magnitude & Direction) উভয়েরই প্রয়োজন হয়। |
| **বীজগণিতীয় নিয়ম** | সাধারণ পাটিগণিত বা বীজগণিতের নিয়মে ($২ + ৩ = ৫$) এদের যোগ, বিয়োগ, গুণ করা যায়। | সাধারণ বীজগণিতের নিয়মে যোগ-বিয়োগ করা যায় না; এরা ভেক্টর বীজগণিতের জ্যামিতিক নিয়ম (যেমন: সামান্তরিক সূত্র, ত্রিভুজ সূত্র) মেনে চলে। |
| **পরিবর্তন** | কেবল মানের পরিবর্তন হলে রাশির পরিবর্তন ঘটে। | ১. কেবল মানের পরিবর্তনে,<br>২. কেবল দিকের পরিবর্তনে, অথবা<br>৩. মান ও দিক উভয়ের পরিবর্তনে পরিবর্তিত হয়। |
| **উদাহরণ** | দৈর্ঘ্য, ভর, সময়, তাপমাত্রা, দ্রুতি, দূরত্ব, কাজ, বিভব, ক্ষমতা, শক্তি, ঘনত্ব ইত্যাদি। | সরণ, বেগ, ত্বরণ, বল, ভরবেগ, বলের ঘাত, মহাকর্ষীয় প্রাবল্য, টর্ক, চৌম্বক আবেশ ইত্যাদি। |

---

### ১.৩ গুরুত্বপূর্ণ অনুধাবনমূলক প্রশ্ন ও ব্যতিক্রমী কেস

#### ❓ প্রশ্ন ১: "তড়িৎপ্রবাহ (Electric Current) দিক থাকা সত্ত্বেও কেন স্কেলার রাশি?"
- **গভীর বৈজ্ঞানিক ব্যাখ্যা:** কোনো রাশি ভেক্টর হতে হলে তাকে কেবল নির্দিষ্ট দিক থাকলেই চলে না, তাকে অবশ্যই **ভেক্টর যোগের নিয়ম (সামান্তরিক সূত্র বা ত্রিভুজ সূত্র)** মেনে চলতে হয়।
- একটি পরিবাহীর সংযোগস্থলে যদি দুটি তার দিয়ে $3\text{ A}$ এবং $4\text{ A}$ প্রবাহ যে কোণেই মিলিত হোক না কেন, তাদের সংযোগস্থলে মোট নির্গমন প্রবাহ সর্বদা সাধারণ পাটিগণিতের নিয়মে $3 + 4 = 7\text{ A}$ হয়। এটি তার দুটির মধ্যবর্তী কোণের ওপর নির্ভর করে না এবং ভেক্টর যোগের সামান্তরিক সূত্র মানে না। তাই নির্দিষ্ট দিক থাকা সত্ত্বেও তড়িৎপ্রবাহ একটি **স্কেলার রাশি**।

#### ❓ প্রশ্ন ২: "চাপ (Pressure) ও পৃষ্ঠটান (Surface Tension) কেন স্কেলার রাশি?"
- **চাপ:** চাপ হলো প্রতি একক ক্ষেত্রফলের ওপর লম্বভাবে প্রযুক্ত বল ($P = F/A$)। কোনো আবদ্ধ তরল বা বায়বীয় পদার্থের অভ্যন্তরে চাপ কোনো একক নির্দিষ্ট দিকে কাজ করে না, বরং পাত্রের দেওয়ালে সকল দিকে অভিলম্বভাবে ক্রিয়া করে। এর কোনো সুনির্দিষ্ট একক অভিমুখ নেই। তাই চাপ স্কেলার রাশি।

---

## ২. ভেক্টরের জ্যামিতিক ও প্রতীকী প্রকাশ

### ২.১ জ্যামিতিক প্রকাশ (Graphical Representation)
একটি নির্দিষ্ট দৈর্ঘ্যের তীরচিহ্নযুক্ত সরলরেখাংশ দ্বারা ভেক্টর রাশিকে জ্যামিতিকভাবে উপস্থাপন করা হয়:

<div class="diagram-box">
<svg viewBox="0 0 460 140" class="physics-diagram">
<defs>
<marker id="arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
</defs>
<line x1="60" y1="70" x2="380" y2="70" stroke="#d97706" stroke-width="4" marker-end="url(#arr-amb)"/>
<circle cx="60" cy="70" r="5.5" fill="var(--text-main)"/>
<text x="35" y="95" fill="var(--text-main)" font-weight="700" font-size="13">পাদবিন্দু O (Tail)</text>
<circle cx="380" cy="70" r="5.5" fill="#d97706"/>
<text x="345" y="95" fill="#d97706" font-weight="700" font-size="13">শীর্ষবিন্দু P (Head)</text>
<text x="210" y="55" fill="#d97706" font-weight="800" font-size="16">A⃗ (ভেক্টর)</text>
<line x1="60" y1="110" x2="380" y2="110" stroke="var(--border-subtle)" stroke-width="1.5" stroke-dasharray="3,3"/>
<text x="180" y="125" fill="var(--text-dim)" font-size="12">দৈর্ঘ্য = মান |A⃗| = A</text>
</svg>
<div class="diagram-caption">চিত্র ২.১: জ্যামিতিকভাবে ভেক্টরের উপস্থাপন (পাদবিন্দু, শীর্ষবিন্দু ও মান)</div>
</div>

1. **পাদবিন্দু বা প্রারম্ভিক বিন্দু (Initial Point / Tail):** যে বিন্দু থেকে ভেক্টর রেখাংশটি শুরু হয় (এখানে $O$ বিন্দু)।
2. **শীর্ষবিন্দু বা প্রান্তবিন্দু (Terminal Point / Head):** যেখানে তীরচিহ্ন শেষ হয় (এখানে $P$ বিন্দু)।
3. **দিক (Direction):** পাদবিন্দু থেকে শীর্ষবিন্দুর অভিমুখই ($O \to P$) ভেক্টরের দিক নির্দেশ করে।
4. **ভেক্টরের মান (Magnitude):** রেখাংশটির দৈর্ঘ্য $OP = |\vec{A}| = A$।

### ২.২ প্রতীকী বা বীজগণিতীয় প্রকাশ (Symbolic Notation)
- **চিহ্ন দ্বারা প্রকাশ:**
  - অক্ষরের মাথায় তীর চিহ্ন দিয়ে: $\vec{A}$
  - মোটা হরফ বা বোল্ড টাইপ করে: $\mathbf{A}$
- **ভেক্টরের পরম মান (Magnitude):** পরম মান চিহ্নের সাহায্যে $|\vec{A}|$ বা $|\mathbf{A}|$ অথবা সাধারণ হরফে কেবল $A$ দিয়ে প্রকাশ করা হয়।

---

## ৩. ভেক্টরের গুরুত্বপূর্ণ প্রকারভেদ (Exhaustive Classification)

### ১. অবস্থান ভেক্টর (Position Vector)
- **সংজ্ঞা:** প্রসঙ্গ কাঠামোর মূলবিন্দুর সাপেক্ষে কোনো বিন্দুর অবস্থান নির্দেশক ভেক্টরকে অবস্থান ভেক্টর বলে।
- **সমীকরণ:** প্রসঙ্গ কাঠামোর মূলবিন্দু $O(0,0,0)$ এবং যেকোনো বিন্দু $P(x,y,z)$ হলে:
  $$\vec{OP} = \vec{r} = x\hat{i} + y\hat{j} + z\hat{k}$$
- **বিশেষ নাম:** অবস্থান ভেক্টরকে **ব্যাসার্ধ ভেক্টর (Radius Vector)**-ও বলা হয়।

### ২. সরণ ভেক্টর (Displacement Vector)
- **সংজ্ঞা:** কোনো গতিশীল কণার আদি অবস্থান ভেক্টর থেকে শেষ অবস্থান ভেক্টরের পরিবর্তনকে সরণ ভেক্টর বলে।
- **সমীকরণ:** কণাটি যদি $P(x_1, y_1, z_1)$ থেকে $Q(x_2, y_2, z_2)$ বিন্দুতে যায়:
  $$\Delta\vec{r} = \vec{r}_2 - \vec{r}_1 = (x_2 - x_1)\hat{i} + (y_2 - y_1)\hat{j} + (z_2 - z_1)\hat{k}$$

### ৩. সমান বা সম ভেক্টর (Equal Vectors)
- **সংজ্ঞা:** একই জাতীয় দুটি ভেক্টরের মান সমান এবং দিক একই হলে তাদেরকে সমান ভেক্টর বলে ($\vec{A} = \vec{B}$)।
- **শর্ত:** $|\vec{A}| = |\vec{B}|$ এবং উভয় ভেক্টর সমান্তরাল ও একই অভিমুখী।

### ৪. বিপরীত বা ঋণাত্মক ভেক্টর (Negative / Opposite Vector)
- **সংজ্ঞা:** নির্দিষ্ট দিক বরাবর কোনো ভেক্টরকে ধনাত্মক ধরলে, তার সমান মানযুক্ত কিন্তু ঠিক বিপরীতমুখী সমজাতীয় ভেক্টরকে ঋণাত্মক বা বিপরীত ভেক্টর বলে ($-\vec{A}$)।
- **শর্ত:** $|\vec{A}| = |-\vec{A}|$ কিন্তু দিক পরস্পর $180^\circ$ বিপরীত।

### ৫. সদৃশ ও বিসদৃশ ভেক্টর (Like & Unlike Vectors)
- **সদৃশ ভেক্টর:** সমজাতীয় দুই বা ততোধিক ভেক্টর যদি একই দিকে সমান্তরালে ক্রিয়া করে (মান সমান হওয়া আবশ্যক নয়)।
- **বিসদৃশ ভেক্টর:** সমজাতীয় দুটি ভেক্টর যদি পরস্পর বিপরীত দিকে ক্রিয়া করে (মান সমান হওয়া আবশ্যক নয়)।

### ৬. সমরেখ ভেক্টর (Collinear Vectors)
- **সংজ্ঞা:** দুই বা ততোধিক ভেক্টর যদি একই সরলরেখা বরাবর বা পরস্পর সমান্তরালে ক্রিয়া করে, তবে তাদেরকে সমরেখ ভেক্টর বলে।

### ৭. সমতলীয় ভেক্টর (Coplanar Vectors)
- **সংজ্ঞা:** দুই বা ততোধিক ভেক্টর যদি একই সমতলে অবস্থান করে, তবে তাদেরকে সমতলীয় ভেক্টর বলে। যেমন: টেবিলের ওপর রাখা সকল ভেক্টর।

### ৮. সহ-প্রারম্ভিক ভেক্টর (Co-initial Vectors)
- **সংজ্ঞা:** দুই বা ততোধিক ভেক্টরের যদি প্রারম্ভিক বিন্দু বা পাদবিন্দু (Tail) একই বিন্দু হয়, তবে তাদেরকে সহ-প্রারম্ভিক ভেক্টর বলে।

### ৯. সঠিক ভেক্টর (Proper Vector)
- **সংজ্ঞা:** যে সকল ভেক্টরের মান অশূন্য ($|\vec{A}| \neq 0$), তাদেরকে সঠিক ভেক্টর বলা হয়।

### ১০. শূন্য বা নাল ভেক্টর (Null or Zero Vector)
- **সংজ্ঞা:** যে ভেক্টরের মান শূন্য, তাকে শূন্য বা নাল ভেক্টর ($\vec{0}$) বলে। এর কোনো নির্দিষ্ট দিক নেই (অনির্ধারিত বা ইচ্ছামতো ধরা যায়)।
- **উৎপত্তি:**
  1. পাদবিন্দু ও শীর্ষবিন্দু একই বিন্দু হলে।
  2. দুটি সমান ও বিপরীতমুখী ভেক্টরের যোগফল একটি শূন্য ভেক্টর ($\vec{A} + (-\vec{A}) = \vec{0}$)।

### ১১. একক ভেক্টর (Unit Vector)
- **সংজ্ঞা:** যে ভেক্টরের মান এক (1) একক, তাকে একক ভেক্টর বলে।
- **নির্ণয়ের নিয়ম:** কোনো অশূন্য ভেক্টরকে তার পরম মান দ্বারা ভাগ করলে ওই ভেক্টরের দিক বরাবর একক ভেক্টর পাওয়া যায়।
  $$\hat{a} = \frac{\vec{A}}{|\vec{A}|} = \frac{\vec{A}}{A}$$
- **আয়ত একক ভেক্টর (Rectangular Unit Vectors):** ত্রিমাত্রিক কার্তেসীয় স্থানাঙ্ক ব্যবস্থায় ধনাত্মক $X$, $Y$ ও $Z$ অক্ষ বরাবর যথাক্রমে $\hat{i}$, $\hat{j}$ ও $\hat{k}$ একক ভেক্টর ধরা হয়।

### ১২. বিপ্রতীপ ভেক্টর (Reciprocal Vector)
- **সংজ্ঞা:** দুটি সমান্তরাল ভেক্টরের একটির মান অপরটির গুণাত্মক বিপরীত (Reciprocal) হলে তাদেরকে বিপ্রতীপ ভেক্টর বলে।
- **উদাহরণ:** $\vec{A} = 6\hat{i}$ হলে এর বিপ্রতীপ ভেক্টর হবে $\vec{B} = \frac{1}{6}\hat{i}$।

---

## ৪. ভেক্টরের মান ও একক ভেক্টর নির্ণয়ের গাণিতিক প্রতিপাদন

<div class="diagram-box">
<svg viewBox="0 0 520 270" class="physics-diagram">
<defs>
<marker id="arr-m" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#78716c"/></marker>
<marker id="arr-r" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<path d="M 70 210 L 250 210 L 440 155 L 260 155 Z" fill="rgba(217, 119, 6, 0.05)" stroke="var(--border-subtle)" stroke-dasharray="3,3"/>
<line x1="70" y1="210" x2="470" y2="210" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arr-m)"/>
<text x="480" y="215" fill="var(--text-main)" font-weight="700" font-size="14">X</text>
<line x1="70" y1="210" x2="70" y2="30" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arr-m)"/>
<text x="65" y="20" fill="var(--text-main)" font-weight="700" font-size="14">Y</text>
<line x1="70" y1="210" x2="270" y2="150" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arr-m)"/>
<text x="280" y="145" fill="var(--text-main)" font-weight="700" font-size="14">Z</text>
<circle cx="70" cy="210" r="4.5" fill="var(--text-main)"/>
<text x="50" y="228" fill="var(--text-main)" font-weight="700" font-size="13">O(0,0,0)</text>
<line x1="70" y1="210" x2="360" y2="70" stroke="#e11d48" stroke-width="3.5" marker-end="url(#arr-r)"/>
<circle cx="360" cy="70" r="5" fill="#e11d48"/>
<text x="370" y="65" fill="#e11d48" font-weight="800" font-size="15">P(Ax, Ay, Az) → A⃗</text>
<line x1="360" y1="70" x2="360" y2="155" stroke="#0d9488" stroke-width="1.8" stroke-dasharray="4,4"/>
<line x1="360" y1="155" x2="360" y2="210" stroke="#78716c" stroke-width="1.5" stroke-dasharray="3,3"/>
<line x1="360" y1="155" x2="165" y2="155" stroke="#78716c" stroke-width="1.5" stroke-dasharray="3,3"/>
<text x="220" y="228" fill="#d97706" font-weight="700" font-size="12">Ax</text>
<text x="15" y="130" fill="#0d9488" font-weight="700" font-size="12">Ay</text>
<text x="180" y="145" fill="#2563eb" font-weight="700" font-size="12">Az</text>
<path d="M 150 210 A 80 80 0 0 0 138 178" fill="none" stroke="#d97706" stroke-width="2"/>
<text x="158" y="195" fill="#d97706" font-weight="700" font-size="13">α</text>
<path d="M 70 135 A 80 80 0 0 0 120 142" fill="none" stroke="#0d9488" stroke-width="2"/>
<text x="90" y="125" fill="#0d9488" font-weight="700" font-size="13">β</text>
<path d="M 130 192 A 70 70 0 0 0 120 170" fill="none" stroke="#2563eb" stroke-width="2"/>
<text x="132" y="172" fill="#2563eb" font-weight="700" font-size="13">γ</text>
</svg>
<div class="diagram-caption">চিত্র ৪.১: ত্রিমাত্রিক আয়ত স্থানাঙ্ক ব্যবস্থায় ভেক্টর $ec{A}$ এবং দিক কোসাইন কোণত্রয় ($lpha, eta, \gamma$)</div>
</div>

### ৪.১ দ্বিমাত্রিক (2D) ক্ষেত্রে মান নির্ণয় (পিথাগোরাসের উপপাদ্য থেকে প্রমাণ)
ধরা যাক, $X$-$Y$ সমতলে একটি ভেক্টর $\vec{A} = A_x\hat{i} + A_y\hat{j}$।
এখানে, $OA = A_x$ (ভূমি) এবং $AP = A_y$ (লম্ব)।
সমকোণী ত্রিভুজ $\triangle OAP$-তে পিথাগোরাসের উপপাদ্য প্রয়োগ করে:

$$\begin{aligned}
\text{অতিভুজ}^2 &= \text{ভূমি}^2 + \text{লম্ব}^2 \\
OP^2 &= OA^2 + AP^2 \\
|\vec{A}|^2 &= A_x^2 + A_y^2 \\[4pt]
\mathbf{|\vec{A}|} &\mathbf{= \sqrt{A_x^2 + A_y^2}}
\end{aligned}$$

### ৪.২ ত্রিমাত্রিক (3D) ক্ষেত্রে মান নির্ণয়
যদি ভেক্টরটি ত্রিমাত্রিক স্থানে অবস্থান করে: $\vec{A} = A_x\hat{i} + A_y\hat{j} + A_z\hat{k}$
$$\mathbf{|\vec{A}| = A = \sqrt{A_x^2 + A_y^2 + A_z^2}}$$

### ৪.৩ একক ভেক্টর নির্ণয়ের পূর্ণাঙ্গ সূত্র
$$\mathbf{\hat{a} = \frac{\vec{A}}{|\vec{A}|} = \frac{A_x\hat{i} + A_y\hat{j} + A_z\hat{k}}{\sqrt{A_x^2 + A_y^2 + A_z^2}}}$$

### ৪.৪ ত্রিমাত্রিক দিক কোসাইন (Direction Cosines) ও প্রতিপাদন
যদি $\vec{A}$ ভেক্টরটি ধনাত্মক $X$, $Y$ ও $Z$ অক্ষের সাথে যথাক্রমে $\alpha$, $\beta$ ও $\gamma$ কোণ তৈরি করে, তবে:
$$\cos\alpha = \frac{A_x}{|\vec{A}|}, \quad \cos\beta = \frac{A_y}{|\vec{A}|}, \quad \cos\gamma = \frac{A_z}{|\vec{A}|}$$

**১ম প্রমাণ: $\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$**
$$\cos^2\alpha + \cos^2\beta + \cos^2\gamma = \frac{A_x^2}{A^2} + \frac{A_y^2}{A^2} + \frac{A_z^2}{A^2} = \frac{A_x^2 + A_y^2 + A_z^2}{A^2} = \frac{A^2}{A^2} = 1$$

**২য় প্রমাণ: $\sin^2\alpha + \sin^2\beta + \sin^2\gamma = 2$**
আমরা জানি $\cos^2\theta = 1 - \sin^2\theta$। মান বসিয়ে:

$$\begin{aligned}
(1 - \sin^2\alpha) + (1 - \sin^2\beta) + (1 - \sin^2\gamma) &= 1 \\
3 - (\sin^2\alpha + \sin^2\beta + \sin^2\gamma) &= 1 \\[4pt]
\mathbf{\sin^2\alpha + \sin^2\beta + \sin^2\gamma} &\mathbf{= 2}
\end{aligned}$$

---

## ৫. ভেক্টর যোজন ও বিয়োজনের জ্যামিতিক ও বীজগণিতীয় নিয়মাবলী

<div class="diagram-grid">
<div class="diagram-box">
<svg viewBox="0 0 320 200" class="physics-diagram">
<defs>
<marker id="t-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="t-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="t-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<line x1="30" y1="160" x2="160" y2="160" stroke="#d97706" stroke-width="3" marker-end="url(#t-arr-amb)"/>
<text x="85" y="182" fill="#d97706" font-weight="700" font-size="13">A⃗</text>
<circle cx="30" cy="160" r="3.5" fill="var(--text-main)"/>
<line x1="160" y1="160" x2="270" y2="60" stroke="#0d9488" stroke-width="3" marker-end="url(#t-arr-tl)"/>
<text x="230" y="115" fill="#0d9488" font-weight="700" font-size="13">B⃗</text>
<circle cx="160" cy="160" r="3.5" fill="var(--text-main)"/>
<line x1="30" y1="160" x2="270" y2="60" stroke="#e11d48" stroke-width="3.5" stroke-dasharray="2,0" marker-end="url(#t-arr-rb)"/>
<text x="120" y="95" fill="#e11d48" font-weight="800" font-size="14">R⃗ = A⃗ + B⃗</text>
<circle cx="270" cy="60" r="4" fill="#e11d48"/>
</svg>
<div class="diagram-caption">চিত্র ৫.১: সাধারণ সূত্র ও ত্রিভুজ সূত্র (Triangle Law)</div>
</div>
<div class="diagram-box">
<svg viewBox="0 0 320 200" class="physics-diagram">
<defs>
<marker id="p-arr-bl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#2563eb"/></marker>
<marker id="p-arr-pu" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#7c3aed"/></marker>
</defs>
<line x1="25" y1="155" x2="105" y2="155" stroke="#d97706" stroke-width="2.5" marker-end="url(#t-arr-amb)"/>
<text x="60" y="175" fill="#d97706" font-weight="700" font-size="12">A⃗</text>
<line x1="105" y1="155" x2="175" y2="100" stroke="#0d9488" stroke-width="2.5" marker-end="url(#t-arr-tl)"/>
<text x="145" y="135" fill="#0d9488" font-weight="700" font-size="12">B⃗</text>
<line x1="175" y1="100" x2="235" y2="50" stroke="#2563eb" stroke-width="2.5" marker-end="url(#p-arr-bl)"/>
<text x="210" y="70" fill="#2563eb" font-weight="700" font-size="12">C⃗</text>
<line x1="235" y1="50" x2="290" y2="90" stroke="#7c3aed" stroke-width="2.5" marker-end="url(#p-arr-pu)"/>
<text x="270" y="65" fill="#7c3aed" font-weight="700" font-size="12">D⃗</text>
<line x1="25" y1="155" x2="290" y2="90" stroke="#e11d48" stroke-width="3.5" marker-end="url(#t-arr-rb)"/>
<text x="120" y="130" fill="#e11d48" font-weight="800" font-size="13">R⃗ = A⃗+B⃗+C⃗+D⃗</text>
</svg>
<div class="diagram-caption">চিত্র ৫.২: বহুভুজ সূত্র (Polygon Law)</div>
</div>
</div>

### ৫.১ সাধারণ সূত্র (Head-to-Tail Rule)
প্রথম ভেক্টরের শীর্ষবিন্দুতে দ্বিতীয় ভেক্টরের পাদবিন্দু স্থাপন করলে প্রথমটির পাদবিন্দু থেকে দ্বিতীয়টির শীর্ষবিন্দুর সংযোজক সরলরেখাটি লব্ধি নির্দেশ করে।

### ৫.২ ত্রিভুজ সূত্র (Triangle Law)
> **বিবৃতি:** কোনো ত্রিভুজের দুটি সন্নিহিত বাহু দ্বারা যদি একই ক্রমে দুটি সমজাতীয় ভেক্টর নির্দেশ করা যায়, তবে ত্রিভুজটির তৃতীয় বাহুটি বিপরীত ক্রমে ভেক্টরদ্বয়ের লব্ধি নির্দেশ করবে।
$$\vec{R} = \vec{A} + \vec{B}$$

### ৫.৩ বহুভুজ সূত্র (Polygon Law)
> **বিবৃতি:** দুইয়ের অধিক ভেক্টরের ক্ষেত্রে ১ম ভেক্টরের শীর্ষবিন্দুতে ২য়টির পাদবিন্দু, ২য়টির শীর্ষে ৩য়টির পাদবিন্দু—এভাবে সাজানোর পর ১ম ভেক্টরের পাদবিন্দু থেকে শেষ ভেক্টরের শীর্ষবিন্দু যোগ করলে বিপরীত ক্রমে লব্ধি পাওয়া যায়।
$$\vec{R} = \vec{A} + \vec{B} + \vec{C} + \vec{D} + \dots$$

### ৫.৪ ভেক্টর যোগের ৩টি মৌলিক বীজগণিতীয় নিয়ম
1. **বিনিময় নিয়ম (Commutative Law):** $\vec{A} + \vec{B} = \vec{B} + \vec{A}$
2. **সংযোগ নিয়ম (Associative Law):** $(\vec{A} + \vec{B}) + \vec{C} = \vec{A} + (\vec{B} + \vec{C})$
3. **বণ্টন নিয়ম (Distributive Law):** $m(\vec{A} + \vec{B}) = m\vec{A} + m\vec{B}$ (যেখানে $m$ একটি স্কেলার)

### ৫.৫ ভেক্টর বিয়োগ (Vector Subtraction)
ভেক্টর বিয়োগ মূলত বিপরীত ভেক্টরের যোগ:
$$\vec{A} - \vec{B} = \vec{A} + (-\vec{B})$$

---

## ৬. সামান্তরিক সূত্র ও তার সম্পূর্ণ গাণিতিক প্রমাণ

<div class="diagram-box">
<svg viewBox="0 0 540 270" class="physics-diagram">
<defs>
<marker id="pl-arr-amb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#d97706"/></marker>
<marker id="pl-arr-tl" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#0d9488"/></marker>
<marker id="pl-arr-rb" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M 0 1.5 L 8 5 L 0 8.5 z" fill="#e11d48"/></marker>
</defs>
<line x1="60" y1="210" x2="310" y2="210" stroke="#d97706" stroke-width="3.5" marker-end="url(#pl-arr-amb)"/>
<text x="180" y="235" fill="#d97706" font-weight="800" font-size="15">P⃗ (OA)</text>
<line x1="60" y1="210" x2="190" y2="55" stroke="#0d9488" stroke-width="3.5" marker-end="url(#pl-arr-tl)"/>
<text x="100" y="125" fill="#0d9488" font-weight="800" font-size="15">Q⃗ (OB)</text>
<line x1="190" y1="55" x2="440" y2="55" stroke="var(--border-subtle)" stroke-width="1.8" stroke-dasharray="5,4"/>
<line x1="310" y1="210" x2="440" y2="55" stroke="#0d9488" stroke-width="2" stroke-dasharray="5,4"/>
<text x="390" y="125" fill="#0d9488" font-weight="700" font-size="13">AC = Q</text>
<line x1="60" y1="210" x2="440" y2="55" stroke="#e11d48" stroke-width="4" marker-end="url(#pl-arr-rb)"/>
<text x="250" y="115" fill="#e11d48" font-weight="800" font-size="16">R⃗ = P⃗ + Q⃗ (কর্ণ OC)</text>
<line x1="310" y1="210" x2="440" y2="210" stroke="var(--text-dim)" stroke-width="1.8" stroke-dasharray="4,4"/>
<line x1="440" y1="55" x2="440" y2="210" stroke="#2563eb" stroke-width="2"/>
<rect x="424" y="194" width="16" height="16" fill="none" stroke="#2563eb" stroke-width="1.2"/>
<circle cx="60" cy="210" r="4.5" fill="var(--text-main)"/>
<text x="45" y="225" fill="var(--text-main)" font-weight="800" font-size="14">O</text>
<circle cx="310" cy="210" r="4.5" fill="var(--text-main)"/>
<text x="305" y="235" fill="var(--text-main)" font-weight="800" font-size="14">A</text>
<circle cx="440" cy="210" r="4.5" fill="var(--text-main)"/>
<text x="445" y="230" fill="var(--text-main)" font-weight="800" font-size="14">D</text>
<circle cx="190" cy="55" r="4.5" fill="var(--text-main)"/>
<text x="175" y="45" fill="var(--text-main)" font-weight="800" font-size="14">B</text>
<circle cx="440" cy="55" r="4.5" fill="#e11d48"/>
<text x="448" y="50" fill="#e11d48" font-weight="800" font-size="14">C</text>
<text x="345" y="228" fill="#d97706" font-size="12" font-weight="700">AD = Q cos α</text>
<text x="448" y="140" fill="#2563eb" font-size="12" font-weight="700">CD = Q sin α</text>
<path d="M 120 210 A 60 60 0 0 0 102 160" fill="none" stroke="#0d9488" stroke-width="2.2"/>
<text x="125" y="185" fill="#0d9488" font-weight="800" font-size="13">α</text>
<path d="M 360 210 A 50 50 0 0 0 348 168" fill="none" stroke="#0d9488" stroke-width="1.8"/>
<text x="365" y="195" fill="#0d9488" font-weight="700" font-size="12">α</text>
<path d="M 150 210 A 90 90 0 0 0 138 178" fill="none" stroke="#e11d48" stroke-width="2.5"/>
<text x="155" y="200" fill="#e11d48" font-weight="800" font-size="13">θ</text>
</svg>
<div class="diagram-caption">চিত্র ৬.১: সামান্তরিক সূত্রের সাহায্যে লব্ধির মান ($R$) ও দিক ($	heta$) নির্ণয়ের সম্পূর্ণ জ্যামিতিক চিত্র ($CD \perp OD$)</div>
</div>

### ৬.১ বিবৃতি
> কোনো সামান্তরিকের একটি বিন্দু থেকে অঙ্কিত দুটি সন্নিহিত বাহু যদি একই সময়ে কোনো কণার ওপর ক্রিয়ারত দুটি সমজাতীয় ভেক্টরের মান ও দিক নির্দেশ করে, তবে ওই বিন্দু থেকে অঙ্কিত সামান্তরিকের কর্ণটিই ভেক্টরদ্বয়ের লব্ধির মান ও দিক নির্দেশ করবে।

### ৬.২ লব্ধির মান ($R$) নির্ণয়ের নিখুঁত জ্যামিতিক প্রমাণ
মনে করি, $O$ বিন্দুতে ক্রিয়ারত দুটি ভেক্টর $\vec{P}$ ও $\vec{Q}$-এর মধ্যবর্তী কোণ $\angle AOB = \alpha$।
$OA = P$, $OB = Q$ ধরে $OACB$ সামান্তরিক অঙ্কন করা হলো। তাহলে কর্ণ $OC = \vec{R}$ হলো লব্ধি।

$OA$ বাহুকে $D$ পর্যন্ত বর্ধিত করি এবং $C$ বিন্দু থেকে $OA$-এর বর্ধিতাংশের ওপর $CD$ লম্ব টানি ($CD \perp OD$)।
যেহেতু $AC \parallel OB$, সুতরাং $AC = OB = Q$ এবং $\angle CAD = \angle AOB = \alpha$।

সমকোণী ত্রিভুজ $\triangle ACD$ হতে:
$$\cos\alpha = \frac{AD}{AC} \implies AD = AC\cos\alpha = Q\cos\alpha$$
$$\sin\alpha = \frac{CD}{AC} \implies CD = AC\sin\alpha = Q\sin\alpha$$

এখন, সমকোণী ত্রিভুজ $\triangle OCD$-তে পিথাগোরাসের উপপাদ্য প্রয়োগ করে:

$$\begin{aligned}
OC^2 &= OD^2 + CD^2 \\
&= (OA + AD)^2 + CD^2 \\
R^2 &= (P + Q\cos\alpha)^2 + (Q\sin\alpha)^2 \\
&= P^2 + 2PQ\cos\alpha + Q^2\cos^2\alpha + Q^2\sin^2\alpha \\
&= P^2 + 2PQ\cos\alpha + Q^2(\cos^2\alpha + \sin^2\alpha) \\
&= P^2 + Q^2 + 2PQ\cos\alpha \quad [\because \cos^2\alpha + \sin^2\alpha = 1] \\[6pt]
\mathbf{R} &\mathbf{= \sqrt{P^2 + Q^2 + 2PQ\cos\alpha}}
\end{aligned}$$

### ৬.৩ লব্ধির দিক ($\theta$) নির্ণয়ের প্রতিপাদন
ধরি, লব্ধি $\vec{R}$ ভেক্টরটি $\vec{P}$ ভেক্টরের সাথে $\theta$ কোণ তৈরি করেছে ($ngle COD = \theta$)।
সমকোণী ত্রিভুজ $\triangle OCD$ হতে:

$$\begin{aligned}
\tan\theta &= \frac{CD}{OD} = \frac{CD}{OA + AD} \\[6pt]
\mathbf{\tan\theta} &\mathbf{= \frac{Q\sin\alpha}{P + Q\cos\alpha}} \\[6pt]
\mathbf{\theta} &\mathbf{= \tan^{-1}\left(\frac{Q\sin\alpha}{P + Q\cos\alpha}\right)}
\end{aligned}$$

> **লব্ধির দিক সংক্রান্ত সোনালি নিয়ম:**
> লব্ধি $R$ যার সাথে $\theta$ কোণ তৈরি করবে (এখানে $P$), সে হরে একাকী বসে থাকবে। আর অপর ভেক্টরটি ($Q$) উপরে $\sin\alpha$ এবং নিচে $\cos\alpha$ নিয়ে গুণ থাকবে।

---

## ৭. লব্ধির বিশেষ ক্ষেত্রসমূহ (Special Cases Table)

| কেস | মধ্যবর্তী কোণ ($\alpha$) | $\cos\alpha$ ও $\sin\alpha$ | লব্ধির মান ($R$) | লব্ধির দিক ($\theta$) | ভৌত তাৎপর্য |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **১. একই দিকে (সমরেখ)** | $\alpha = 0^\circ$ | $\cos 0^\circ = 1$<br>$\sin 0^\circ = 0$ | $\mathbf{R_{\max} = P + Q}$ | $\theta = 0^\circ$ | লব্ধির মান সর্বোচ্চ হয়। |
| **২. বিপরীত দিকে** | $\alpha = 180^\circ$ | $\cos 180^\circ = -1$<br>$\sin 180^\circ = 0$ | $\mathbf{R_{\min} = |P - Q|}$ | $\theta = 0^\circ$ (বৃহত্তর বলের দিকে) | লব্ধির মান সর্বনিম্ন হয়। |
| **৩. পরস্পর লম্বভাবে** | $\alpha = 90^\circ$ | $\cos 90^\circ = 0$<br>$\sin 90^\circ = 1$ | $\mathbf{R = \sqrt{P^2 + Q^2}}$ | $\tan\theta = \frac{Q}{P}$ | সমকোণে ক্রিয়ারত পিথাগোরাস কেস। |
| **৪. সমান মানের ভেক্টর** | $P = Q$ | যেকোনো $\alpha$ | $\mathbf{R = 2P\cos\left(\frac{\alpha}{2}\right)}$ | $\theta = \frac{\alpha}{2}$ | লব্ধি মধ্যবর্তী কোণকে সমদ্বিখণ্ডিত করে। |
| **৫. লব্ধি ক্ষুদ্রতর বলের ওপর লম্ব** | $\theta = 90^\circ$ ($P$-এর ওপর) | $\tan 90^\circ = \infty$ | $\mathbf{R = \sqrt{Q^2 - P^2}}$ | $\cos\alpha = -\frac{P}{Q}$ | এখানে অবশ্যই $Q > P$ হতে হবে। |

### প্রমাণ: সমান মানের ভেক্টরের ক্ষেত্রে $R = 2P\cos(\alpha/2)$

$$\begin{aligned}
R &= \sqrt{P^2 + P^2 + 2P^2\cos\alpha} \\
&= \sqrt{2P^2(1 + \cos\alpha)} \\
&= \sqrt{2P^2 \cdot 2\cos^2(\alpha/2)} \quad [\because 1 + \cos\alpha = 2\cos^2(\alpha/2)] \\
&= \sqrt{4P^2\cos^2(\alpha/2)} \\[4pt]
\mathbf{R} &\mathbf{= 2P\cos\left(\frac{\alpha}{2}\right)}
\end{aligned}$$

---

## ৮. টাইপভিত্তিক সমাধানকৃত গাণিতিক সমস্যা (Worked Examples)

### 📌 টাইপ ১: দ্বিমাত্রিক ও ত্রিমাত্রিক ভেক্টরের মান ও একক ভেক্টর
**সমস্যা ১:** একটি ৩D ভেক্টর $\vec{P} = 2\hat{i} - 3\hat{j} + 6\hat{k}$ দেওয়া আছে।
১. ভেক্টরটির পরম মান $|\vec{P}|$ কত?
২. $\vec{P}$-এর দিক বরাবর একক ভেক্টর $\hat{p}$ নির্ণয় করো।

**সমাধান:**
- **ধাপ ১ (সহগ চিহ্নিতকরণ):** $P_x = 2$, $P_y = -3$, $P_z = 6$
- **ধাপ ২ (মান নির্ণয়):**
  $$|\vec{P}| = \sqrt{(2)^2 + (-3)^2 + (6)^2} = \sqrt{4 + 9 + 36} = \sqrt{49} = \mathbf{7\text{ একক}}$$
- **ধাপ ৩ (একক ভেক্টর):**
  $$\hat{p} = \frac{\vec{P}}{|\vec{P}|} = \frac{2\hat{i} - 3\hat{j} + 6\hat{k}}{7} = \mathbf{\frac{2}{7}\hat{i} - \frac{3}{7}\hat{j} + \frac{6}{7}\hat{k}}$$

---

### 📌 টাইপ ২: দুটি বিন্দুর স্থানাঙ্ক থেকে সরণ ভেক্টর
**সমস্যা ২:** ত্রিমাত্রিক স্থানে দুটি বিন্দু $A(1, 2, 3)$ এবং $B(4, 6, 8)$। সরণ ভেক্টর $\vec{AB}$ এবং এর মান নির্ণয় করো।

**সমাধান:**
- **ধাপ ১ (সরণ ভেক্টর গঠন):**
  $$\vec{AB} = (x_2 - x_1)\hat{i} + (y_2 - y_1)\hat{j} + (z_2 - z_1)\hat{k}$$
  $$\vec{AB} = (4 - 1)\hat{i} + (6 - 2)\hat{j} + (8 - 3)\hat{k} = \mathbf{3\hat{i} + 4\hat{j} + 5\hat{k}}$$
- **ধাপ ২ (মান নির্ণয়):**
  $$|\vec{AB}| = \sqrt{3^2 + 4^2 + 5^2} = \sqrt{9 + 16 + 25} = \sqrt{50} = \mathbf{5\sqrt{2}\text{ একক}}$$

---

### 📌 টাইপ ৩: সামান্তরিক সূত্রের সাধারণ প্রয়োগ
**সমস্যা ৩:** $3\text{ N}$ এবং $4\text{ N}$ মানের দুটি বল একটি বিন্দুতে $60^\circ$ কোণে ক্রিয়ারত। লব্ধির মান ও দিক নির্ণয় করো।

**সমাধান:**
দেওয়া আছে: $P = 3\text{ N}$, $Q = 4\text{ N}$, $\alpha = 60^\circ$
1. **লব্ধির মান:**
   $$R = \sqrt{3^2 + 4^2 + 2(3)(4)\cos 60^\circ} = \sqrt{9 + 16 + 24(0.5)} = \sqrt{25 + 12} = \sqrt{37} \approx \mathbf{6.08\text{ N}}$$
2. **লব্ধির দিক ($P$-এর সাথে কোণ):**
   $$\tan\theta = \frac{4\sin 60^\circ}{3 + 4\cos 60^\circ} = \frac{4(0.866)}{3 + 4(0.5)} = \frac{3.464}{5} = 0.6928$$
   $$\theta = \tan^{-1}(0.6928) \approx \mathbf{34.71^\circ}$$

---

### 📌 টাইপ ৪: দুটি সমান বল ও ১২০° কোণ
**সমস্যা ৪:** $5\text{ N}$ ও $5\text{ N}$ মানের দুটি বল $120^\circ$ কোণে ক্রিয়ারত থাকলে এদের লব্ধির মান ও দিক কত?

**সমাধান:**
যেহেতু $P = Q = 5\text{ N}$ এবং $\alpha = 120^\circ$:
$$R = 2P\cos\left(\frac{\alpha}{2}\right) = 2(5)\cos 60^\circ = 10 \times 0.5 = \mathbf{5\text{ N}}$$
$$\theta = \frac{\alpha}{2} = \frac{120^\circ}{2} = \mathbf{60^\circ}$$

---

### 📌 টাইপ ৫: বুয়েট / এডমিশন স্পেশাল (লব্ধি ক্ষুদ্রতর বলের ওপর লম্ব)
**সমস্যা ৫:** দুটি বলের লব্ধি ক্ষুদ্রতর বলের ওপর লম্ব এবং এর মান বৃহত্তর বলের মানের এক-তৃতীয়াংশ। বলদ্বয়ের মানের অনুপাত কত?

**সমাধান:**
ধরি ক্ষুদ্রতর বল $P$ এবং বৃহত্তর বল $Q$। লব্ধি $\vec{R} \perp \vec{P}$, অর্থাৎ $\theta = 90^\circ$।
শর্তমতে: $R = \frac{1}{3}Q$
আমরা জানি, যখন লব্ধি ক্ষুদ্রতর বলের ওপর লম্ব হয়:
$$R^2 = Q^2 - P^2$$
$$\left(\frac{1}{3}Q\right)^2 = Q^2 - P^2 \implies \frac{1}{9}Q^2 = Q^2 - P^2$$
$$P^2 = Q^2 - \frac{1}{9}Q^2 = \frac{8}{9}Q^2 \implies \frac{P^2}{Q^2} = \frac{8}{9}$$
$$\mathbf{\frac{P}{Q} = \frac{\sqrt{8}}{3} = \frac{2\sqrt{2}}{3}}$$

---

## ৯. স্ব-মূল্যায়ন ও প্র্যাকটিস চ্যালেঞ্জ (Self-Practice Problems with Hints & Solutions)

<div class="practice-card">
<div class="practice-header">
<span class="practice-badge">প্র্যাকটিস ০১</span>
<h4>দিক কোসাইন ও কোণ সংক্রান্ত সমস্যা</h4>
</div>
<p><strong>প্রশ্ন:</strong> একটি ভেক্টর $\vec{A} = 2\hat{i} - 2\hat{j} + \hat{k}$।</p>
<ol>
<li>ভেক্টরটির দিক কোসাইনত্রয় $(\cos\alpha, \cos\beta, \cos\gamma)$ নির্ণয় করো।</li>
<li>ভেক্টরটি $Y$-অক্ষের সাথে কত কোণ তৈরি করে?</li>
<li>যাচাই করো যে $\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$।</li>
</ol>
<details class="practice-collapse">
<summary class="practice-summary">💡 সমাধান ও উত্তর দেখতে ক্লিক করুন</summary>
<div class="practice-solution">
<p><strong>সমাধান:</strong></p>
<p>ভেক্টরের মান: $A = \sqrt{2^2 + (-2)^2 + 1^2} = \sqrt{4 + 4 + 1} = \sqrt{9} = 3$</p>
<p>১. দিক কোসাইনত্রয়:</p>
<ul>
<li>$\cos\alpha = \frac{A_x}{A} = \mathbf{\frac{2}{3}}$</li>
<li>$\cos\beta = \frac{A_y}{A} = \mathbf{-\frac{2}{3}}$</li>
<li>$\cos\gamma = \frac{A_z}{A} = \mathbf{\frac{1}{3}}$</li>
</ul>
<p>২. $Y$-অক্ষের সাথে কোণ $\beta = \cos^{-1}\left(-\frac{2}{3}\right) = \mathbf{131.81^\circ}$</p>
<p>৩. $\cos^2\alpha + \cos^2\beta + \cos^2\gamma = \left(\frac{2}{3}\right)^2 + \left(-\frac{2}{3}\right)^2 + \left(\frac{1}{3}\right)^2 = \frac{4}{9} + \frac{4}{9} + \frac{1}{9} = \frac{9}{9} = 1$ (যাচাইকৃত)।</p>
</div>
</details>
</div>

<div class="practice-card">
<div class="practice-header">
<span class="practice-badge">প্র্যাকটিস ০২</span>
<h4>সমান বলদ্বয়ের লব্ধি ও মধ্যবর্তী কোণ</h4>
</div>
<p><strong>প্রশ্ন:</strong> দুটি সমান মানের বল একটি বিন্দুতে ক্রিয়াশীল। এদের লব্ধির বর্গ বলদ্বয়ের গুণফলের ৩ গুণ হলে বলদ্বয়ের মধ্যবর্তী কোণ কত?</p>
<details class="practice-collapse">
<summary class="practice-summary">💡 সমাধান ও উত্তর দেখতে ক্লিক করুন</summary>
<div class="practice-solution">
<p><strong>সমাধান:</strong></p>
<p>ধরি, বলদ্বয় $P = Q$ এবং মধ্যবর্তী কোণ $\alpha$।</p>
<p>প্রশ্নমতে: $R^2 = 3(P \times Q) = 3P^2$</p>
<p>সামান্তরিক সূত্র থেকে: $R^2 = P^2 + P^2 + 2P^2\cos\alpha = 2P^2(1 + \cos\alpha)$</p>
<p>অতএব, $2P^2(1 + \cos\alpha) = 3P^2 \implies 1 + \cos\alpha = \frac{3}{2} \implies \cos\alpha = \frac{1}{2}$</p>
<p>$\mathbf{\alpha = \cos^{-1}(0.5) = 60^\circ}$ (উত্তর)</p>
</div>
</details>
</div>

<div class="practice-card">
<div class="practice-header">
<span class="practice-badge">প্র্যাকটিস ০৩</span>
<h4>সর্বোচ্চ ও সর্বনিম্ন লব্ধি থেকে কোণ নির্ণয় (BUET Standard)</h4>
</div>
<p><strong>প্রশ্ন:</strong> কোনো বিন্দুতে ক্রিয়ারত দুটি বলের সর্বোচ্চ লব্ধি $17\text{ N}$ এবং সর্বনিম্ন লব্ধি $7\text{ N}$। বলদ্বয় যদি পরস্পর সমকোণে ($90^\circ$) ক্রিয়া করে, তবে লব্ধির মান কত হবে?</p>
<details class="practice-collapse">
<summary class="practice-summary">💡 সমাধান ও উত্তর দেখতে ক্লিক করুন</summary>
<div class="practice-solution">
<p><strong>সমাধান:</strong></p>
<p>আমরা জানি: $P + Q = 17$ এবং $P - Q = 7$</p>
<p>যোগ করে: $2P = 24 \implies P = 12\text{ N}$</p>
<p>বিয়োগ করে: $2Q = 10 \implies Q = 5\text{ N}$</p>
<p>সমকোণে ক্রিয়ারত হলে লব্ধি:</p>
<p>$\mathbf{R = \sqrt{P^2 + Q^2} = \sqrt{12^2 + 5^2} = \sqrt{144 + 25} = \sqrt{169} = 13\text{ N}}$ (উত্তর)</p>
</div>
</details>
</div>
