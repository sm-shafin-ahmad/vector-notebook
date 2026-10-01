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
  <svg viewBox="0 0 540 280" class="physics-diagram">
    <!-- Grid and Coordinate Planes -->
    <path d="M 80 220 L 260 220 L 460 160 L 280 160 Z" fill="rgba(217, 119, 6, 0.05)" stroke="var(--border-subtle)" stroke-dasharray="3,3"/>
    <path d="M 80 220 L 80 50 L 280 50 L 280 160 L 80 220" fill="rgba(13, 148, 136, 0.04)" stroke="var(--border-subtle)" stroke-dasharray="3,3"/>
    
    <!-- Axes -->
    <!-- X-Axis -->
    <line x1="80" y1="220" x2="480" y2="220" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arrow-muted)"/>
    <text x="490" y="225" fill="var(--text-main)" font-weight="700" font-size="14">X</text>
    
    <!-- Y-Axis -->
    <line x1="80" y1="220" x2="80" y2="30" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arrow-muted)"/>
    <text x="75" y="20" fill="var(--text-main)" font-weight="700" font-size="14">Y</text>
    
    <!-- Z-Axis (Isometric angle) -->
    <line x1="80" y1="220" x2="290" y2="155" stroke="var(--text-main)" stroke-width="2" marker-end="url(#arrow-muted)"/>
    <text x="300" y="150" fill="var(--text-main)" font-weight="700" font-size="14">Z</text>
    
    <!-- Origin -->
    <circle cx="80" cy="220" r="4" fill="var(--text-main)"/>
    <text x="65" y="238" fill="var(--text-main)" font-weight="700" font-size="13">O (0,0,0)</text>

    <!-- 3D Vector A -->
    <line x1="80" y1="220" x2="380" y2="70" stroke="#e11d48" stroke-width="3.5" marker-end="url(#arrow-ruby)"/>
    <circle cx="380" cy="70" r="5" fill="#e11d48"/>
    <text x="390" y="65" fill="#e11d48" font-weight="800" font-size="15">P (Ax, Ay, Az) → A⃗</text>

    <!-- Component Projections -->
    <line x1="380" y1="70" x2="380" y2="160" stroke="#0d9488" stroke-width="1.8" stroke-dasharray="4,4"/>
    <line x1="380" y1="160" x2="380" y2="220" stroke="#78716c" stroke-width="1.5" stroke-dasharray="3,3"/>
    <line x1="380" y1="160" x2="180" y2="160" stroke="#78716c" stroke-width="1.5" stroke-dasharray="3,3"/>
    <line x1="80" y1="70" x2="380" y2="70" stroke="#0d9488" stroke-width="1.5" stroke-dasharray="4,4"/>
    
    <!-- Labels on Axes -->
    <text x="230" y="238" fill="#d97706" font-weight="700" font-size="12">Ax (X-উপাংশ)</text>
    <text x="15" y="140" fill="#0d9488" font-weight="700" font-size="12">Ay (Y-উপাংশ)</text>
    <text x="190" y="150" fill="#2563eb" font-weight="700" font-size="12">Az (Z-উপাংশ)</text>

    <!-- Angle Arcs -->
    <!-- Alpha (with X) -->
    <path d="M 160 220 A 80 80 0 0 0 148 186" fill="none" stroke="#d97706" stroke-width="2"/>
    <text x="168" y="205" fill="#d97706" font-weight="700" font-size="13">α</text>

    <!-- Beta (with Y) -->
    <path d="M 80 140 A 80 80 0 0 0 132 146" fill="none" stroke="#0d9488" stroke-width="2"/>
    <text x="100" y="130" fill="#0d9488" font-weight="700" font-size="13">β</text>

    <!-- Gamma (with Z) -->
    <path d="M 140 201 A 70 70 0 0 0 130 178" fill="none" stroke="#2563eb" stroke-width="2"/>
    <text x="142" y="180" fill="#2563eb" font-weight="700" font-size="13">γ</text>
  </svg>
  <div class="diagram-caption">চিত্র ৪.১: ত্রিমাত্রিক আয়ত স্থানাঙ্ক ব্যবস্থায় ভেক্টর $ec{A}$ এবং দিক কোসাইন কোণত্রয় ($lpha, eta, \gamma$)</div>
</div>

                Y ▲
                  │          P (Ax, Ay)
                  │         /│
                  │        / │
                  │    A⃗  /  │ Ay
                  │      /   │
                  │     /θ   │
                  O────┴─────┴──────► X
                       Ax

<div class="diagram-box">
  <svg viewBox="0 0 540 270" class="physics-diagram">
    <!-- Parallelogram Body -->
    <!-- OA (P) -->
    <line x1="60" y1="210" x2="310" y2="210" stroke="#d97706" stroke-width="3.5" marker-end="url(#arrow-amber)"/>
    <text x="180" y="235" fill="#d97706" font-weight="800" font-size="15">P⃗ (OA)</text>

    <!-- OB (Q) -->
    <line x1="60" y1="210" x2="190" y2="55" stroke="#0d9488" stroke-width="3.5" marker-end="url(#arrow-teal)"/>
    <text x="100" y="125" fill="#0d9488" font-weight="800" font-size="15">Q⃗ (OB)</text>

    <!-- Parallelogram upper lines (Dotted) -->
    <line x1="190" y1="55" x2="440" y2="55" stroke="var(--border-subtle)" stroke-width="1.8" stroke-dasharray="5,4"/>
    <line x1="310" y1="210" x2="440" y2="55" stroke="#0d9488" stroke-width="2" stroke-dasharray="5,4"/>
    <text x="390" y="125" fill="#0d9488" font-weight="700" font-size="13">AC = Q</text>

    <!-- Resultant OC (R) -->
    <line x1="60" y1="210" x2="440" y2="55" stroke="#e11d48" stroke-width="4" marker-end="url(#arrow-ruby)"/>
    <text x="250" y="115" fill="#e11d48" font-weight="800" font-size="16">R⃗ = P⃗ + Q⃗ (কর্ণ OC)</text>

    <!-- Extension AD and Perpendicular CD -->
    <line x1="310" y1="210" x2="440" y2="210" stroke="var(--text-dim)" stroke-width="1.8" stroke-dasharray="4,4"/>
    <line x1="440" y1="55" x2="440" y2="210" stroke="#2563eb" stroke-width="2"/>
    <rect x="424" y="194" width="16" height="16" fill="none" stroke="#2563eb" stroke-width="1.2"/>
    
    <!-- Labels for D, C, A, B, O -->
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

    <!-- Component formula texts -->
    <text x="345" y="228" fill="#d97706" font-size="12" font-weight="700">AD = Q cos α</text>
    <text x="448" y="140" fill="#2563eb" font-size="12" font-weight="700">CD = Q sin α</text>

    <!-- Angle Arcs -->
    <!-- Alpha (between P and Q) -->
    <path d="M 120 210 A 60 60 0 0 0 102 160" fill="none" stroke="#0d9488" stroke-width="2.2"/>
    <text x="125" y="185" fill="#0d9488" font-weight="800" font-size="13">α</text>

    <!-- Alpha at A -->
    <path d="M 360 210 A 50 50 0 0 0 348 168" fill="none" stroke="#0d9488" stroke-width="1.8"/>
    <text x="365" y="195" fill="#0d9488" font-weight="700" font-size="12">α</text>

    <!-- Theta (between P and R) -->
    <path d="M 150 210 A 90 90 0 0 0 138 178" fill="none" stroke="#e11d48" stroke-width="2.5"/>
    <text x="155" y="200" fill="#e11d48" font-weight="800" font-size="13">θ</text>
  </svg>
  <div class="diagram-caption">চিত্র ৬.১: সামান্তরিক সূত্রের সাহায্যে লব্ধির মান ($R$) ও দিক ($	heta$) নির্ণয়ের সম্পূর্ণ জ্যামিতিক চিত্র ($CD \perp OD$)</div>
</div>


### ৬.২ লব্ধির মান ($R$) নির্ণয়ের নিখুঁত জ্যামিতিক প্রমাণ
মনে করি, $O$ বিন্দুতে ক্রিয়ারত দুটি ভেক্টর $\vec{P}$ ও $\vec{Q}$-এর মধ্যবর্তী কোণ $\angle AOB = \alpha$।
$OA = P$, $OB = Q$ ধরে $OACB$ সামান্তরিক অঙ্কন করা হলো। তাহলে কর্ণ $OC = \vec{R}$ হলো লব্ধি।

$OA$ বাহুকে $D$ পর্যন্ত বর্ধিত করি এবং $C$ বিন্দু থেকে $OA$-এর বর্ধিতাংশের ওপর $CD$ লম্ব টানি ($CD \perp OD$)।
যেহেতু $AC \parallel OB$, সুতরাং $AC = OB = Q$ এবং $\angle CAD = \angle AOB = \alpha$।

সমকোণী ত্রিভুজ $\triangle ACD$ হতে:
$$\cos\alpha = \frac{AD}{AC} \implies AD = AC\cos\alpha = Q\cos\alpha$$
$$\sin\alpha = \frac{CD}{AC} \implies CD = AC\sin\alpha = Q\sin\alpha$$

এখন, সমকোণী ত্রিভুজ $\triangle OCD$-তে পিথাগোরাসের উপপাদ্য প্রয়োগ করে:
$$OC^2 = OD^2 + CD^2$$
$$OC^2 = (OA + AD)^2 + CD^2$$
$$R^2 = (P + Q\cos\alpha)^2 + (Q\sin\alpha)^2$$
$$R^2 = P^2 + 2PQ\cos\alpha + Q^2\cos^2\alpha + Q^2\sin^2\alpha$$
$$R^2 = P^2 + 2PQ\cos\alpha + Q^2(\cos^2\alpha + \sin^2\alpha)$$
$$R^2 = P^2 + Q^2 + 2PQ\cos\alpha \quad [\because \cos^2\alpha + \sin^2\alpha = 1]$$

$$\mathbf{R = \sqrt{P^2 + Q^2 + 2PQ\cos\alpha}}$$

### ৬.৩ লব্ধির দিক ($\theta$) নির্ণয়ের প্রতিপাদন
ধরি, লব্ধি $\vec{R}$ ভেক্টরটি $\vec{P}$ ভেক্টরের সাথে $\theta$ কোণ তৈরি করেছে ($\angle COD = \theta$)।
সমকোণী ত্রিভুজ $\triangle OCD$ হতে:
$$\tan\theta = \frac{CD}{OD} = \frac{CD}{OA + AD}$$
$$\mathbf{\tan\theta = \frac{Q\sin\alpha}{P + Q\cos\alpha}}$$
$$\mathbf{\theta = \tan^{-1}\left(\frac{Q\sin\alpha}{P + Q\cos\alpha}\right)}$$

> **লব্ধির দিক সংক্রান্ত সোনালি নিয়ম:**
> লব্ধি $R$ যার সাথে $\theta$ কোণ তৈরি করবে (এখানে $P$), সে হরে একাকী বসে থাকবে। আর অপর ভেক্টরটি ($Q$) উপরে $\sin\alpha$ এবং নিচে $\cos\alpha$ নিয়ে গুণ থাকবে।
> যদি লব্ধি $Q$ ভেক্টরের সাথে $\theta_Q$ কোণ তৈরি করে:
> $$\tan\theta_Q = \frac{P\sin\alpha}{Q + P\cos\alpha}$$

---

## ৭. লব্ধির বিশেষ ক্ষেত্রসমূহ (Special Cases Table)

| কেস | মধ্যবর্তী কোণ ($\alpha$) | $\cos\alpha$ ও $\sin\alpha$ | লব্ধির মান ($R$) | লব্ধির দিক ($\theta$) | ভৌত তাৎপর্য |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **১. একই দিকে (সমরেখ)** | $\alpha = 0^\circ$ | $\cos 0^\circ = 1$<br>$\sin 0^\circ = 0$ | $\mathbf{R_{\max} = P + Q}$ | $\theta = 0^\circ$ | লব্ধির মান সর্বোচ্চ হয়। |
| **২. বিপরীত দিকে** | $\alpha = 180^\circ$ | $\cos 180^\circ = -1$<br>$\sin 180^\circ = 0$ | $\mathbf{R_{\min} = \|P - Q\|}$ | $\theta = 0^\circ$ (বৃহত্তর বলের দিকে) | লব্ধির মান সর্বনিম্ন হয়। |
| **৩. পরস্পর লম্বভাবে** | $\alpha = 90^\circ$ | $\cos 90^\circ = 0$<br>$\sin 90^\circ = 1$ | $\mathbf{R = \sqrt{P^2 + Q^2}}$ | $\tan\theta = \frac{Q}{P}$ | সমকোণে ক্রিয়ারত পিথাগোরাস কেস। |
| **৪. সমান মানের ভেক্টর** | $P = Q$ | যেকোনো $\alpha$ | $\mathbf{R = 2P\cos\left(\frac{\alpha}{2}\right)}$ | $\theta = \frac{\alpha}{2}$ | লব্ধি মধ্যবর্তী কোণকে সমদ্বিখণ্ডিত করে। |
| **৫. লব্ধি ক্ষুদ্রতর বলের ওপর লম্ব** | $\theta = 90^\circ$ ($P$-এর ওপর) | $\tan 90^\circ = \infty$ | $\mathbf{R = \sqrt{Q^2 - P^2}}$ | $\cos\alpha = -\frac{P}{Q}$ | এখানে অবশ্যই $Q > P$ হতে হবে। |

### প্রমাণ: সমান মানের ভেক্টরের ক্ষেত্রে $R = 2P\cos(\alpha/2)$
$$R = \sqrt{P^2 + P^2 + 2P^2\cos\alpha} = \sqrt{2P^2(1 + \cos\alpha)}$$
ত্রিকোণমিতিক সূত্রমতে $1 + \cos\alpha = 2\cos^2(\alpha/2)$
$$R = \sqrt{2P^2 \cdot 2\cos^2(\alpha/2)} = \sqrt{4P^2\cos^2(\alpha/2)} = \mathbf{2P\cos\left(\frac{\alpha}{2}\right)}$$

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
> **গুরুত্বপূর্ণ সিদ্ধান্ত:** দুটি সমান মানের ভেক্টর $120^\circ$ কোণে ক্রিয়া করলে তাদের লব্ধির মান বলদ্বয়ের যেকোনো একটির মানের সমান হয়।

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
