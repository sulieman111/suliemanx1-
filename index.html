<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>تعلم مع سليمان — بايثون من الصفر إلى الاحتراف</title>
<style>
:root{
  --ink:#1B2A41;
  --paper:#F2F5F8;
  --surface:#FFFFFF;
  --line:#D5DDE6;
  --blue:#3B6EA5;
  --blue-soft:#DCE8F4;
  --sun:#F6C945;
  --ok:#217A5C;
  --ok-soft:#DDF1E8;
  --bad:#B63D35;
  --bad-soft:#F8E0DD;
  --muted:#58677A;
  --code-bg:#14202F;
  --code-fg:#E8EEF5;
  color-scheme: light;
}
@media (prefers-color-scheme: dark){
  :root{
    --ink:#E8EEF5;
    --paper:#101822;
    --surface:#18232F;
    --line:#2C3B4B;
    --blue:#7DAEE0;
    --blue-soft:#223445;
    --sun:#F6C945;
    --ok:#5CC29B;
    --ok-soft:#173528;
    --bad:#F08A81;
    --bad-soft:#3B1E1B;
    --muted:#9AA9BA;
    --code-bg:#0B121A;
    --code-fg:#E8EEF5;
    color-scheme: dark;
  }
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;background:var(--paper);color:var(--ink);
  font-family:"Segoe UI","Noto Naskh Arabic","Geeza Pro",Tahoma,system-ui,sans-serif;
  line-height:1.9;font-size:17px;
}
code,textarea,pre{font-family:ui-monospace,"SF Mono",Menlo,Consolas,monospace}
code{direction:ltr;unicode-bidi:isolate;background:var(--blue-soft);color:var(--ink);padding:1px 7px;border-radius:5px;font-size:.92em}
button{font:inherit;cursor:pointer}
:focus-visible{outline:3px solid var(--sun);outline-offset:2px}

/* top bar */
.top{position:sticky;top:0;z-index:10;background:var(--ink);color:#F2F5F8;display:flex;align-items:center;gap:16px;padding:10px 20px}
@media (prefers-color-scheme: dark){.top{background:#0A1017}}
.brand{display:flex;align-items:center;gap:10px;background:none;border:0;color:inherit;padding:0;font-weight:800;font-size:19px}
.brand .mark{width:30px;height:30px;border-radius:8px;background:linear-gradient(135deg,#3B6EA5 50%,#F6C945 50%);flex:none}
.top .grow{flex:1}
.meter{display:flex;align-items:center;gap:10px;font-size:14px;min-width:0}
.meter .bar{width:120px;height:8px;border-radius:99px;background:rgba(255,255,255,.2);overflow:hidden}
.meter .bar i{display:block;height:100%;background:var(--sun);width:0;transition:width .4s}

.wrap{max-width:980px;margin:0 auto;padding:0 20px}

/* hero */
.hero{padding:56px 0 40px;display:grid;grid-template-columns:1.1fr 1fr;gap:40px;align-items:center}
.hero h1{font-size:clamp(38px,6vw,64px);line-height:1.15;margin:0 0 16px;font-weight:900;letter-spacing:-.5px}
.hero p.lead{font-size:19px;color:var(--muted);margin:0 0 26px;max-width:34em}
.cta{background:var(--sun);color:#1B2A41;border:0;border-radius:10px;padding:13px 26px;font-weight:800;font-size:18px}
.cta:hover{filter:brightness(.95)}
.ghost{background:transparent;color:var(--ink);border:2px solid var(--line);border-radius:10px;padding:11px 20px;font-weight:700;margin-inline-start:10px}
.demo{background:var(--code-bg);color:var(--code-fg);border-radius:14px;padding:20px;direction:ltr;text-align:left;box-shadow:0 14px 40px rgba(20,32,47,.25)}
.demo label{display:block;font-family:inherit;font-size:13px;color:#9FB2C7;direction:rtl;text-align:right;margin-bottom:6px}
.demo input{width:100%;background:#0B121A;border:1px solid #2C3B4B;color:#fff;border-radius:8px;padding:9px 12px;font-size:16px;margin-bottom:14px;direction:rtl;font-family:inherit}
.demo pre{margin:0;white-space:pre-wrap;word-break:break-word;font-size:15px;line-height:1.8}
.demo .c{color:#7E92A8}.demo .s{color:#F6C945}.demo .k{color:#8CC0F5}
.demo .out{margin-top:12px;padding-top:12px;border-top:1px dashed #2C3B4B;color:#7ee0b4;direction:rtl;text-align:right;font-family:inherit;font-size:17px}
@media(max-width:760px){.hero{grid-template-columns:1fr;padding-top:32px}}

/* roadmap */
h2.sec{font-size:30px;margin:30px 0 6px}
.sub{color:var(--muted);margin:0 0 24px}
.level{margin-bottom:34px}
.level-head{display:flex;align-items:baseline;gap:12px;flex-wrap:wrap;margin-bottom:8px}
.level-head h3{margin:0;font-size:23px}
.level-head span{color:var(--muted);font-size:15px}
.path{list-style:none;margin:0;padding:0;position:relative}
.path::before{content:"";position:absolute;inset-block:14px;inset-inline-start:17px;width:3px;background:var(--line);border-radius:3px}
.path li{position:relative;padding-inline-start:52px}
.node{width:100%;text-align:right;background:none;border:0;color:inherit;padding:9px 0;display:flex;align-items:center;gap:10px;border-radius:8px}
.node::before{content:attr(data-n);position:absolute;inset-inline-start:0;top:50%;transform:translateY(-50%);width:36px;height:36px;border-radius:50%;background:var(--surface);border:3px solid var(--line);display:grid;place-items:center;font-weight:800;font-size:14px}
.node:hover .t{color:var(--blue)}
.node .t{font-weight:700;font-size:18px}
.node .d{color:var(--muted);font-size:14px}
.node.done::before{content:"✓";background:var(--ok);border-color:var(--ok);color:#fff}
.node.cur::before{border-color:var(--sun);background:var(--sun);color:#1B2A41}

/* lesson */
.lesson{padding:28px 0 60px;max-width:780px;margin:0 auto}
.crumb{background:none;border:0;color:var(--blue);padding:0;font-weight:700;margin-bottom:10px}
.lesson h1{font-size:clamp(28px,4.5vw,40px);line-height:1.3;margin:4px 0 4px}
.tag{color:var(--muted);font-size:15px;margin-bottom:18px}
.lesson p,.lesson li{max-width:42em}
.lesson ul{padding-inline-start:22px}
.block{margin:26px 0}
.block h3{margin:0 0 8px;font-size:21px}
.editor{border-radius:12px;overflow:hidden;background:var(--code-bg);margin:10px 0}
.editor textarea{display:block;width:100%;min-height:130px;resize:vertical;background:transparent;color:var(--code-fg);border:0;padding:16px;font-size:15px;line-height:1.7;direction:ltr;text-align:left;tab-size:4}
.editor textarea:focus{outline:none;box-shadow:inset 0 0 0 2px var(--sun)}
.editor .bar{display:flex;gap:8px;align-items:center;padding:8px 12px;background:#0B121A;border-top:1px solid #2C3B4B}
.run{background:var(--sun);color:#1B2A41;border:0;border-radius:7px;padding:6px 16px;font-weight:800}
.mini{background:transparent;border:1px solid #3A4B5E;color:#C9D6E4;border-radius:7px;padding:5px 12px;font-size:14px}
.status{color:#9FB2C7;font-size:13px;margin-inline-start:auto}
.output{margin:0;padding:12px 16px;background:#0B121A;color:#7ee0b4;white-space:pre-wrap;direction:ltr;text-align:left;font-size:14px;min-height:0}
.output.err{color:#F5A29B}
.output:empty{display:none}
.task{background:var(--blue-soft);border-inline-start:5px solid var(--blue);padding:14px 18px;border-radius:8px;margin-bottom:6px}
.task p{margin:0}
.quiz .q{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:16px 18px;margin-bottom:14px}
.quiz .q p{margin:0 0 10px;font-weight:700}
.opts{display:grid;gap:8px}
.opt{text-align:right;background:var(--paper);border:2px solid var(--line);color:var(--ink);border-radius:9px;padding:9px 14px}
.opt:hover:not(:disabled){border-color:var(--blue)}
.opt.right{background:var(--ok-soft);border-color:var(--ok)}
.opt.wrong{background:var(--bad-soft);border-color:var(--bad)}
.opt code{background:transparent;padding:0}
.fb{margin-top:8px;font-size:15px;min-height:1.2em}
.fb.good{color:var(--ok)}.fb.no{color:var(--bad)}
.nav{display:flex;justify-content:space-between;gap:10px;margin-top:34px;flex-wrap:wrap}
.nav button{border:2px solid var(--line);background:var(--surface);color:var(--ink);border-radius:10px;padding:10px 20px;font-weight:700}
.nav button.primary{background:var(--ink);border-color:var(--ink);color:var(--paper)}
.badge-done{display:inline-block;background:var(--ok-soft);color:var(--ok);border-radius:99px;padding:2px 14px;font-size:14px;font-weight:700;margin-inline-start:8px}
details.sol summary{cursor:pointer;color:var(--blue);font-weight:700;margin:8px 0}
footer{border-top:1px solid var(--line);color:var(--muted);text-align:center;padding:24px 20px;font-size:15px}
@media (prefers-reduced-motion: reduce){*{transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>

<header class="top">
  <button class="brand" id="homeBtn" aria-label="الصفحة الرئيسية"><span class="mark"></span>تعلم مع سليمان</button>
  <span class="grow"></span>
  <div class="meter"><span id="meterTxt">0 من 0 دروس</span><div class="bar"><i id="meterBar"></i></div></div>
</header>

<main id="app"></main>

<footer>تعلم مع سليمان — بايثون من الصفر إلى الاحتراف. تقدّمك محفوظ أثناء بقاء الصفحة مفتوحة.</footer>

<script>
/* ============ محتوى الدروس ============ */
const LEVELS = [
  {id:1, name:"المستوى الأول: البداية", desc:"لا تحتاج أي خبرة سابقة"},
  {id:2, name:"المستوى الثاني: الأساسيات", desc:"تبني برامج صغيرة حقيقية"},
  {id:3, name:"المستوى الثالث: المتوسط", desc:"تكتب كود أنظف وأقوى"},
  {id:4, name:"المستوى الرابع: الاحتراف", desc:"أدوات ومشاريع كما في الشغل الفعلي"}
];

const LESSONS = [
/* ---------- المستوى 1 ---------- */
{lv:1, title:"ما هي بايثون؟ وأول برنامج", sum:"التثبيت وأمر print",
body:`<p>بايثون لغة برمجة سهلة القراءة، وتُستخدم في الويب وتحليل البيانات والذكاء الاصطناعي والأتمتة. كودها قريب من الإنجليزية العادية، لذلك هي أفضل بداية للمبتدئ.</p>
<p><b>التثبيت:</b> نزّل بايثون من الموقع الرسمي <code>python.org</code>، وعلّم على خيار Add to PATH أثناء التثبيت، ثم اكتب <code>python --version</code> في الطرفية للتأكد. ولو لا تريد تثبيت شيء الآن، استخدم Google Colab أو المحرر الموجود في هذه الصفحة.</p>
<p>أول أمر تتعلمه هو <code>print()</code>، وهو يطبع أي شيء على الشاشة. النص يوضع بين علامتي تنصيص.</p>`,
code:`print("مرحباً بالعالم")
print("أنا أتعلم بايثون")
print(2 + 3)`,
task:"اطبع اسمك في سطر، ثم اطبع نتيجة 10 × 4 في سطر ثانٍ.",
starter:`# اكتب كودك هنا
`,
solution:`print("سليمان")
print(10 * 4)`,
quiz:[
 {q:"ما وظيفة الأمر print؟", o:["يحفظ ملفاً","يعرض شيئاً على الشاشة","يحذف متغيراً"], a:1},
 {q:"أي سطر صحيح لطباعة كلمة hello؟", o:["print(hello)","print('hello')","show 'hello'"], a:1}
]},

{lv:1, title:"المتغيرات", sum:"تخزين القيم وتسميتها",
body:`<p>المتغير صندوق له اسم تضع فيه قيمة لتستخدمها لاحقاً. تنشئه بعلامة <code>=</code>، وهي هنا معناها «خزّن» وليست «يساوي».</p>
<ul><li>الاسم يبدأ بحرف أو <code>_</code> ولا يحتوي مسافات.</li><li>بايثون حساسة لحالة الأحرف: <code>age</code> غير <code>Age</code>.</li><li>اختر أسماء واضحة مثل <code>price</code> بدل <code>x</code>.</li></ul>
<p>مثال رقمي: لو <code>x = 5</code> ثم كتبت <code>x = x + 2</code> يصبح <code>x</code> يساوي 7.</p>`,
code:`price = 120
discount = 20
final = price - discount
print(final)

x = 5
x = x + 2
print(x)`,
task:"عرّف متغيرين: length = 8 و width = 3، ثم اطبع مساحة المستطيل (الطول × العرض).",
starter:`length = 8
`,
solution:`length = 8
width = 3
print(length * width)`,
quiz:[
 {q:"ما قيمة y بعد: y = 4 ثم y = y * 3 ؟", o:["4","7","12"], a:2},
 {q:"أي اسم متغير غير صحيح؟", o:["my_age","2price","total"], a:1}
]},

{lv:1, title:"أنواع البيانات", sum:"int و float و str و bool",
body:`<p>لكل قيمة نوع. الأنواع الأربعة الأساسية:</p>
<ul><li><code>int</code> عدد صحيح مثل 7</li><li><code>float</code> عدد عشري مثل 3.14</li><li><code>str</code> نص مثل "أحمد"</li><li><code>bool</code> قيمة منطقية: <code>True</code> أو <code>False</code></li></ul>
<p>الدالة <code>type()</code> تخبرك بنوع القيمة، ويمكنك التحويل بين الأنواع بـ <code>int()</code> و <code>float()</code> و <code>str()</code>. تنبيه شائع: <code>"5" + "5"</code> يعطي <code>"55"</code> لأن النصوص تُلصق ببعضها، بينما <code>5 + 5</code> يعطي 10.</p>`,
code:`print(type(7))
print(type(3.14))
print(type("نص"))
print(type(True))

print("5" + "5")
print(int("5") + int("5"))`,
task:"حوّل النص \"12\" إلى عدد، ثم اطبع ناتج ضربه في 3.",
starter:`n = "12"
`,
solution:`n = "12"
print(int(n) * 3)`,
quiz:[
 {q:"ما ناتج \"2\" + \"3\" ؟", o:["5","23","خطأ"], a:1},
 {q:"ما نوع القيمة 3.0 ؟", o:["int","float","str"], a:1}
]},

{lv:1, title:"العمليات والنصوص", sum:"الحساب و f-string والمدخلات",
body:`<p>العمليات الحسابية: <code>+</code> جمع، <code>-</code> طرح، <code>*</code> ضرب، <code>/</code> قسمة عشرية، <code>//</code> قسمة صحيحة، <code>%</code> باقي القسمة، <code>**</code> أس. مثال: <code>17 // 5</code> تساوي 3 و <code>17 % 5</code> تساوي 2.</p>
<p>لدمج المتغيرات داخل نص استخدم الـ f-string: ضع حرف <code>f</code> قبل النص واكتب المتغير بين أقواس معقوفة. ولاستقبال مدخل من المستخدم استخدم <code>input()</code> وتذكّر أنها ترجع نصاً دائماً.</p>`,
code:`name = "سليمان"
age = 20
print(f"اسمي {name} وعمري {age}")

print(17 // 5)
print(17 % 5)
print(2 ** 10)`,
task:"عندك السعر 250 والكمية 4. اطبع جملة بالشكل: الإجمالي = 1000 (احسبه بالكود داخل f-string).",
starter:`price = 250
qty = 4
`,
solution:`price = 250
qty = 4
print(f"الإجمالي = {price * qty}")`,
quiz:[
 {q:"ما ناتج 17 % 5 ؟", o:["3","2","3.4"], a:1},
 {q:"ما نوع القيمة التي ترجعها input() ؟", o:["int","str","حسب ما يكتب المستخدم"], a:1}
]},

{lv:1, title:"الشروط if / elif / else", sum:"اتخاذ القرارات في البرنامج",
body:`<p>الشرط يجعل البرنامج يختار مساراً حسب حالة معينة. المقارنات: <code>==</code> يساوي، <code>!=</code> لا يساوي، <code>&gt;</code> <code>&lt;</code> <code>&gt;=</code> <code>&lt;=</code>. ويمكن الجمع بين الشروط بـ <code>and</code> و <code>or</code> و <code>not</code>.</p>
<p><b>مهم جداً:</b> المسافة البادئة (4 مسافات) داخل الشرط جزء من الصياغة، وهي التي تحدد ما يتبع الشرط.</p>`,
code:`score = 78

if score >= 90:
    print("ممتاز")
elif score >= 70:
    print("جيد")
else:
    print("حاول مرة أخرى")`,
task:"اكتب شرطاً: لو العمر age أكبر من أو يساوي 18 اطبع «مسموح»، وإلا اطبع «غير مسموح». جرّب age = 16.",
starter:`age = 16
`,
solution:`age = 16
if age >= 18:
    print("مسموح")
else:
    print("غير مسموح")`,
quiz:[
 {q:"ما الفرق بين = و == ؟", o:["لا فرق","= للتخزين و == للمقارنة","= للمقارنة و == للتخزين"], a:1},
 {q:"لو score = 70 في المثال أعلاه، ماذا يُطبع؟", o:["ممتاز","جيد","حاول مرة أخرى"], a:1}
]},

{lv:1, title:"الحلقات for و while", sum:"تكرار العمل بدون نسخ الكود",
body:`<p>الحلقة تكرر مجموعة أوامر. <code>for</code> مناسبة عندما تعرف عدد التكرارات أو عندك مجموعة عناصر، و <code>while</code> مناسبة عندما تكرر حتى يتحقق شرط.</p>
<p>الدالة <code>range(5)</code> تعطي الأرقام 0 و1 و2 و3 و4 (تتوقف قبل الرقم الأخير). والأمر <code>break</code> يوقف الحلقة، و <code>continue</code> يقفز للدورة التالية.</p>`,
code:`for i in range(1, 6):
    print(i, "×", 3, "=", i * 3)

n = 3
while n > 0:
    print(n)
    n = n - 1
print("انطلق!")`,
task:"اطبع مجموع الأرقام من 1 إلى 100 باستخدام حلقة for (الناتج المتوقع 5050).",
starter:`total = 0
`,
solution:`total = 0
for i in range(1, 101):
    total += i
print(total)`,
quiz:[
 {q:"كم مرة تتكرر حلقة for i in range(4) ؟", o:["3","4","5"], a:1},
 {q:"ماذا يفعل break ؟", o:["يتخطى دورة واحدة","يوقف الحلقة كلها","يعيد الحلقة من البداية"], a:1}
]},

/* ---------- المستوى 2 ---------- */
{lv:2, title:"القوائم Lists", sum:"تخزين مجموعة عناصر",
body:`<p>القائمة تحفظ عناصر مرتبة داخل أقواس مربعة. الترقيم يبدأ من 0، فأول عنصر في <code>nums[0]</code> وآخر عنصر في <code>nums[-1]</code>.</p>
<p>أهم الأوامر: <code>append</code> لإضافة عنصر، <code>remove</code> للحذف بالقيمة، <code>len</code> للعدد، <code>sort</code> للترتيب، والتقطيع <code>nums[1:3]</code> يعطي العناصر 1 و2.</p>`,
code:`nums = [10, 20, 30]
nums.append(40)
print(nums)
print(nums[0], nums[-1])
print(nums[1:3])
print(len(nums), sum(nums))

for n in nums:
    print(n * 2)`,
task:"عندك القائمة [5, 3, 9, 1]. اطبعها مرتبة تصاعدياً، ثم اطبع أكبر قيمة فيها باستخدام max.",
starter:`data = [5, 3, 9, 1]
`,
solution:`data = [5, 3, 9, 1]
data.sort()
print(data)
print(max(data))`,
quiz:[
 {q:"ما قيمة [4, 8, 15][1] ؟", o:["4","8","15"], a:1},
 {q:"أي أمر يضيف عنصراً في آخر القائمة؟", o:["append","remove","len"], a:0}
]},

{lv:2, title:"القواميس والمجموعات", sum:"dict و tuple و set",
body:`<p>القاموس يخزن أزواج «مفتاح: قيمة» ويسمح بالوصول السريع بالاسم بدل الرقم.</p>
<ul><li><code>dict</code>: مثل <code>{"name": "علي", "age": 22}</code></li><li><code>tuple</code>: قائمة ثابتة لا تتغير <code>(1, 2)</code></li><li><code>set</code>: مجموعة بلا تكرار <code>{1, 2, 2, 3}</code> تصبح <code>{1, 2, 3}</code></li></ul>`,
code:`student = {"name": "علي", "age": 22}
student["city"] = "القاهرة"
print(student["name"])
print(student.get("phone", "غير موجود"))

for key, value in student.items():
    print(key, "->", value)

print(set([1, 2, 2, 3, 3]))`,
task:"اصنع قاموساً لكتاب فيه title و price، ثم اطبع السعر بعد زيادته 10.",
starter:`book = {"title": "بايثون", "price": 100}
`,
solution:`book = {"title": "بايثون", "price": 100}
book["price"] += 10
print(book["price"])`,
quiz:[
 {q:"ماذا يعطي set([1,1,2]) ؟", o:["{1, 1, 2}","{1, 2}","خطأ"], a:1},
 {q:"كيف تقرأ قيمة المفتاح name من القاموس d ؟", o:["d.name","d[\"name\"]","d(name)"], a:1}
]},

{lv:2, title:"الدوال Functions", sum:"إعادة استخدام الكود",
body:`<p>الدالة كتلة كود لها اسم، تكتبها مرة وتستدعيها كلما احتجتها. تُعرَّف بـ <code>def</code>، وتستقبل مُدخلات (parameters)، وترجع نتيجة بـ <code>return</code>.</p>
<p>يمكنك وضع قيمة افتراضية للمدخل. والمتغيرات المعرَّفة داخل الدالة لا تُرى خارجها.</p>`,
code:`def area(w, h=1):
    return w * h

print(area(4, 5))
print(area(7))

def greet(name):
    return f"أهلاً {name}"

print(greet("سليمان"))`,
task:"اكتب دالة is_even(n) ترجع True لو العدد زوجي. جرّبها على 10 و 7.",
starter:`def is_even(n):
    pass
`,
solution:`def is_even(n):
    return n % 2 == 0

print(is_even(10))
print(is_even(7))`,
quiz:[
 {q:"ماذا ترجع دالة بلا return ؟", o:["0","None","نص فارغ"], a:1},
 {q:"ما ناتج area(7) في المثال؟", o:["7","1","خطأ"], a:0}
]},

{lv:2, title:"التعامل مع الأخطاء", sum:"try / except",
body:`<p>الأخطاء تحدث حتى عند المحترفين، والمهم ألا ينهار البرنامج. ضع الكود الخطر داخل <code>try</code> واكتب في <code>except</code> ما يحدث عند الخطأ.</p>
<p>أشهر الأخطاء: <code>ValueError</code> قيمة غير مناسبة، <code>ZeroDivisionError</code> قسمة على صفر، <code>KeyError</code> مفتاح غير موجود. الأفضل أن تلتقط نوع الخطأ المحدد وليس كل الأخطاء.</p>`,
code:`def safe_div(a, b):
    try:
        return a / b
    except ZeroDivisionError:
        return "لا يمكن القسمة على صفر"

print(safe_div(10, 2))
print(safe_div(5, 0))

try:
    int("abc")
except ValueError:
    print("هذا ليس رقماً")`,
task:"اكتب كوداً يحاول تحويل \"x7\" إلى int، ويطبع «إدخال غير صالح» عند الفشل.",
starter:`value = "x7"
`,
solution:`value = "x7"
try:
    print(int(value))
except ValueError:
    print("إدخال غير صالح")`,
quiz:[
 {q:"أي خطأ يظهر من int(\"abc\") ؟", o:["KeyError","ValueError","ZeroDivisionError"], a:1},
 {q:"أين نضع الكود الذي قد يفشل؟", o:["داخل try","داخل except","بعد else فقط"], a:0}
]},

{lv:2, title:"قراءة وكتابة الملفات", sum:"حفظ البيانات على القرص",
body:`<p>لفتح ملف استخدم <code>open</code> داخل <code>with</code> لأنها تغلق الملف تلقائياً. الأوضاع: <code>"r"</code> قراءة، <code>"w"</code> كتابة (تمسح القديم)، <code>"a"</code> إضافة في النهاية.</p>
<p>اكتب دائماً <code>encoding="utf-8"</code> حتى تعمل العربية بدون مشاكل.</p>`,
code:`with open("notes.txt", "w", encoding="utf-8") as f:
    f.write("السطر الأول\\n")
    f.write("السطر الثاني\\n")

with open("notes.txt", "r", encoding="utf-8") as f:
    for line in f:
        print(line.strip())`,
task:"اكتب ثلاثة أسماء في ملف names.txt (اسم في كل سطر) ثم اقرأه واطبع عدد الأسطر.",
starter:`names = ["أحمد", "منى", "كريم"]
`,
solution:`names = ["أحمد", "منى", "كريم"]
with open("names.txt", "w", encoding="utf-8") as f:
    for n in names:
        f.write(n + "\\n")

with open("names.txt", "r", encoding="utf-8") as f:
    print(len(f.readlines()))`,
quiz:[
 {q:"أي وضع يمسح محتوى الملف القديم؟", o:["r","w","a"], a:1},
 {q:"لماذا نستخدم with ؟", o:["لتسريع الكود","لإغلاق الملف تلقائياً","لتشفير الملف"], a:1}
]},

{lv:2, title:"المكتبات والوحدات", sum:"import و pip",
body:`<p>بايثون تأتي مع مكتبات جاهزة (مثل <code>math</code> و <code>random</code> و <code>datetime</code>) وتستدعيها بـ <code>import</code>. وهناك آلاف المكتبات الخارجية تُثبَّت بالأداة <code>pip</code> مثل: <code>pip install requests</code>.</p>
<p>وأي ملف <code>.py</code> تكتبه يمكنك استيراده في ملف آخر، وبهذا تقسّم مشروعك إلى أجزاء منظمة.</p>`,
code:`import math
import random
from datetime import date

print(math.sqrt(144))
print(random.randint(1, 6))
print(date.today().year)`,
task:"استخدم random.choice لاختيار عنصر عشوائي من القائمة [\"حجر\", \"ورقة\", \"مقص\"] واطبعه.",
starter:`import random
`,
solution:`import random
print(random.choice(["حجر", "ورقة", "مقص"]))`,
quiz:[
 {q:"ما الأداة التي تثبّت المكتبات الخارجية؟", o:["pip","print","def"], a:0},
 {q:"ماذا تعطي math.sqrt(144) ؟", o:["12.0","14.4","72"], a:0}
]},

/* ---------- المستوى 3 ---------- */
{lv:3, title:"List Comprehension و lambda", sum:"كود أقصر وأوضح",
body:`<p>الـ list comprehension طريقة مختصرة لبناء قائمة من قائمة أخرى في سطر واحد: <code>[تعبير for عنصر in مصدر if شرط]</code>.</p>
<p>والـ lambda دالة صغيرة بلا اسم، تُستخدم كثيراً مع <code>sorted</code> و <code>map</code> و <code>filter</code>.</p>`,
code:`nums = [1, 2, 3, 4, 5, 6]
squares = [n * n for n in nums]
evens = [n for n in nums if n % 2 == 0]
print(squares)
print(evens)

words = ["python", "go", "javascript"]
print(sorted(words, key=lambda w: len(w)))`,
task:"من القائمة [3, 8, 12, 5, 20] ابنِ قائمة بالأعداد الأكبر من 6 مضروبة في 2 في سطر واحد.",
starter:`data = [3, 8, 12, 5, 20]
`,
solution:`data = [3, 8, 12, 5, 20]
print([n * 2 for n in data if n > 6])`,
quiz:[
 {q:"ما ناتج [n + 1 for n in [1, 2, 3]] ؟", o:["[1, 2, 3]","[2, 3, 4]","[3, 4, 5]"], a:1},
 {q:"ما هي lambda ؟", o:["مكتبة خارجية","دالة صغيرة بلا اسم","نوع بيانات"], a:1}
]},

{lv:3, title:"البرمجة الكائنية: Classes", sum:"الصنف والكائن والخصائص",
body:`<p>الصنف (class) قالب لإنشاء كائنات تجمع بيانات وسلوكاً معاً. مثلاً الصنف <code>Account</code> يحتوي الرصيد (بيانات) والإيداع والسحب (سلوك).</p>
<p>الدالة <code>__init__</code> تعمل تلقائياً عند إنشاء الكائن لتجهيز خصائصه، والكلمة <code>self</code> تشير إلى الكائن نفسه.</p>`,
code:`class Account:
    def __init__(self, owner, balance=0):
        self.owner = owner
        self.balance = balance

    def deposit(self, amount):
        self.balance += amount

    def withdraw(self, amount):
        if amount > self.balance:
            print("الرصيد غير كافٍ")
        else:
            self.balance -= amount

acc = Account("سليمان", 100)
acc.deposit(50)
acc.withdraw(500)
print(acc.balance)`,
task:"أنشئ صنف Rectangle له w و h ودالة area ترجع المساحة. اطبع مساحة Rectangle(3, 4).",
starter:`class Rectangle:
    pass
`,
solution:`class Rectangle:
    def __init__(self, w, h):
        self.w = w
        self.h = h

    def area(self):
        return self.w * self.h

print(Rectangle(3, 4).area())`,
quiz:[
 {q:"ماذا تعني self داخل الصنف؟", o:["الكائن الحالي","اسم الصنف","مكتبة خارجية"], a:0},
 {q:"متى تعمل __init__ ؟", o:["عند إنشاء كائن جديد","عند حذف الكائن","عند طباعة الكائن"], a:0}
]},

{lv:3, title:"الوراثة والدوال الخاصة", sum:"إعادة استخدام الأصناف",
body:`<p>الوراثة تجعل صنفاً جديداً يأخذ كل ما في صنف قديم ثم يضيف أو يعدّل عليه. نكتب اسم الصنف الأب بين قوسين، ونستدعيه بـ <code>super()</code>.</p>
<p>الدوال التي تبدأ وتنتهي بشرطتين سفليتين مثل <code>__str__</code> و <code>__len__</code> تتحكم بسلوك كائنك مع أوامر بايثون المدمجة.</p>`,
code:`class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        return "..."

class Cat(Animal):
    def speak(self):
        return "مياو"

    def __str__(self):
        return f"قطة اسمها {self.name}"

c = Cat("لولو")
print(c.speak())
print(c)`,
task:"أنشئ صنف Dog يرث من Animal ويرجع \"هاو\" من speak. اطبع c.speak() لكلب اسمه ريكس.",
starter:`class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        return "..."
`,
solution:`class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        return "..."

class Dog(Animal):
    def speak(self):
        return "هاو"

print(Dog("ريكس").speak())`,
quiz:[
 {q:"ماذا تفعل super() ؟", o:["تحذف الصنف الأب","تستدعي دوال الصنف الأب","تنشئ كائناً جديداً"], a:1},
 {q:"أي دالة تحدد نص الكائن عند print ؟", o:["__init__","__str__","__len__"], a:1}
]},

{lv:3, title:"Generators و Decorators", sum:"مفاهيم تفرّق المحترف",
body:`<p><b>المولّد (generator)</b> دالة تستخدم <code>yield</code> بدل <code>return</code>، فتعطي القيم واحدة واحدة عند الطلب بدون تخزين الكل في الذاكرة. ممتاز مع البيانات الضخمة.</p>
<p><b>الديكوريتر (decorator)</b> دالة تأخذ دالة أخرى وتضيف لها سلوكاً (مثل قياس الزمن أو التسجيل) بدون تعديلها. يُكتب فوق الدالة بعلامة <code>@</code>.</p>`,
code:`def countdown(n):
    while n > 0:
        yield n
        n -= 1

print(list(countdown(4)))

def shout(func):
    def wrapper(*args):
        return func(*args).upper()
    return wrapper

@shout
def hello(name):
    return "hello " + name

print(hello("sulieman"))`,
task:"اكتب مولّداً evens(limit) يعطي الأعداد الزوجية من 2 حتى limit، واطبع list(evens(10)).",
starter:`def evens(limit):
    pass
`,
solution:`def evens(limit):
    for n in range(2, limit + 1, 2):
        yield n

print(list(evens(10)))`,
quiz:[
 {q:"ما ميزة yield ؟", o:["تُرجع قيمة واحدة وتنتهي","تُنتج القيم تدريجياً وتوفر الذاكرة","تحذف الدالة"], a:1},
 {q:"ما الرمز الذي يُكتب قبل اسم الديكوريتر؟", o:["#","@","$"], a:1}
]},

/* ---------- المستوى 4 ---------- */
{lv:4, title:"البيئات الافتراضية و Git", sum:"تنظيم مشروع حقيقي",
body:`<p>كل مشروع يحتاج مكتباته الخاصة، لذلك ننشئ <b>بيئة افتراضية</b> معزولة حتى لا تتعارض نسخ المكتبات بين المشاريع.</p>
<p>الأوامر في الطرفية (وليس داخل بايثون):</p>
<ul><li><code>python -m venv .venv</code> لإنشاء البيئة</li><li><code>source .venv/bin/activate</code> للتفعيل (على ويندوز <code>.venv\\Scripts\\activate</code>)</li><li><code>pip freeze &gt; requirements.txt</code> لتسجيل المكتبات</li></ul>
<p>و<b>Git</b> يحفظ تاريخ مشروعك: <code>git init</code> ثم <code>git add .</code> ثم <code>git commit -m "رسالة"</code>. ارفع مشاريعك على GitHub لتبني ملف أعمال يراه أصحاب العمل.</p>`,
code:`# هيكل مشروع مرتب (للقراءة)
my_project/
    .venv/
    app/
        __init__.py
        main.py
    tests/
        test_main.py
    requirements.txt
    README.md`,
task:"اكتب على ورقة الأوامر الثلاثة لإنشاء بيئة افتراضية وتفعيلها وحفظ مكتباتها، وجرّبها على جهازك.",
starter:`# الأوامر تُنفَّذ في الطرفية
`,
solution:`python -m venv .venv
source .venv/bin/activate
pip freeze > requirements.txt`,
quiz:[
 {q:"لماذا نستخدم البيئات الافتراضية؟", o:["لتسريع الإنترنت","لعزل مكتبات كل مشروع","لتشفير الكود"], a:1},
 {q:"أي ملف يسجل مكتبات المشروع؟", o:["README.md","requirements.txt","main.py"], a:1}
]},

{lv:4, title:"الاختبارات و Type Hints", sum:"كود موثوق يمكن صيانته",
body:`<p><b>Type hints</b> تكتب نوع المدخل والمخرج لتوضيح الكود وتساعد المحرر على كشف الأخطاء مبكراً: <code>def add(a: int, b: int) -&gt; int</code>.</p>
<p><b>الاختبارات الآلية</b> كود يتأكد أن كودك يعمل. المكتبة الأشهر <code>pytest</code>: تكتب دوال تبدأ بـ <code>test_</code> وفيها <code>assert</code>، ثم تشغّل الأمر <code>pytest</code>.</p>`,
code:`def add(a: int, b: int) -> int:
    return a + b

def test_add():
    assert add(2, 3) == 5
    assert add(-1, 1) == 0

test_add()
print("كل الاختبارات نجحت")`,
task:"اكتب دالة multiply بـ type hints، واختبرها بـ assert على 3×4 = 12.",
starter:`def multiply(a: int, b: int) -> int:
    pass
`,
solution:`def multiply(a: int, b: int) -> int:
    return a * b

assert multiply(3, 4) == 12
print("نجح")`,
quiz:[
 {q:"ماذا يحدث عندما يفشل assert ؟", o:["يتجاهله بايثون","يظهر خطأ AssertionError","يُحذف الاختبار"], a:1},
 {q:"ماذا تعني الإشارة -> int ؟", o:["الدالة ترجع int","الدالة تستقبل int فقط","الدالة تطبع int"], a:0}
]},

{lv:4, title:"JSON و APIs وقواعد البيانات", sum:"التعامل مع بيانات العالم الحقيقي",
body:`<p>الـ <b>API</b> بوابة يرسل إليها برنامجك طلباً فيرد بالبيانات، وغالباً بصيغة <b>JSON</b> (تشبه القواميس تماماً). المكتبة الشائعة لذلك <code>requests</code>: <code>requests.get(url).json()</code>.</p>
<p>ولحفظ البيانات بشكل دائم نستخدم قواعد البيانات. بايثون تأتي مع <code>sqlite3</code> وهي مثالية للتعلم: تنشئ جداول وتكتب عليها بلغة SQL.</p>`,
code:`import json, sqlite3

data = json.loads('{"name": "علي", "score": 90}')
print(data["name"], data["score"])

db = sqlite3.connect(":memory:")
db.execute("CREATE TABLE users (name TEXT, score INTEGER)")
db.execute("INSERT INTO users VALUES (?, ?)", ("علي", 90))
db.execute("INSERT INTO users VALUES (?, ?)", ("منى", 95))
rows = db.execute("SELECT name FROM users WHERE score > 92").fetchall()
print(rows)`,
task:"أضف مستخدماً ثالثاً بدرجة 88 في الجدول، ثم اطبع متوسط الدرجات بـ SELECT AVG(score).",
starter:`import sqlite3
db = sqlite3.connect(":memory:")
db.execute("CREATE TABLE users (name TEXT, score INTEGER)")
`,
solution:`import sqlite3
db = sqlite3.connect(":memory:")
db.execute("CREATE TABLE users (name TEXT, score INTEGER)")
for n, s in [("علي", 90), ("منى", 95), ("كريم", 88)]:
    db.execute("INSERT INTO users VALUES (?, ?)", (n, s))
print(db.execute("SELECT AVG(score) FROM users").fetchone()[0])`,
quiz:[
 {q:"ما صيغة JSON التي تشبهها في بايثون؟", o:["القاموس dict","المجموعة set","الـ tuple"], a:0},
 {q:"أي مكتبة مدمجة للتعامل مع SQLite ؟", o:["requests","sqlite3","flask"], a:1}
]},

{lv:4, title:"الويب والبيانات والمشروع النهائي", sum:"FastAPI و pandas وخطتك للاحتراف",
body:`<p>الآن تختار مسارك:</p>
<ul><li><b>تطوير الويب:</b> <code>FastAPI</code> أو <code>Django</code> لبناء مواقع وواجهات API.</li><li><b>تحليل البيانات:</b> <code>pandas</code> و <code>matplotlib</code> لقراءة الجداول وتحليلها ورسمها.</li><li><b>الذكاء الاصطناعي:</b> <code>numpy</code> ثم <code>scikit-learn</code> ثم <code>PyTorch</code>.</li><li><b>الأتمتة:</b> سكربتات تنظم الملفات وترسل الرسائل وتجمع البيانات.</li></ul>
<p><b>المشروع النهائي المقترح:</b> برنامج تتبّع مصروفات يحفظ في SQLite، ويعرض إحصاءات، ويُرفع على GitHub مع README واختبارات. هذا المشروع يجمع كل ما تعلمته.</p>
<p>المحترف لا يعرف كل شيء، لكنه يتقن القراءة والبحث وتقسيم المشكلة إلى خطوات صغيرة، وهذا ما تدرّبت عليه طوال الدروس.</p>`,
code:`# مثال مصغّر من تحليل البيانات (بدون مكتبات خارجية)
expenses = {"طعام": 1200, "مواصلات": 400, "ترفيه": 300}
total = sum(expenses.values())

for name, amount in expenses.items():
    pct = amount / total * 100
    print(f"{name}: {amount} ({pct:.1f}%)")`,
task:"طوّر المثال: اطبع أيضاً اسم أكبر بند صرف باستخدام max مع key.",
starter:`expenses = {"طعام": 1200, "مواصلات": 400, "ترفيه": 300}
`,
solution:`expenses = {"طعام": 1200, "مواصلات": 400, "ترفيه": 300}
biggest = max(expenses, key=expenses.get)
print(biggest)`,
quiz:[
 {q:"أي مكتبة تناسب تحليل الجداول؟", o:["pandas","random","math"], a:0},
 {q:"ما أفضل طريقة لتثبيت ما تعلمته؟", o:["مشاهدة الدروس فقط","بناء مشاريع صغيرة وحقيقية","حفظ الأوامر"], a:1}
]}
];

/* ============ الحالة ============ */
const state = {view:"home", i:0, done:new Set(), answers:{}};
const app = document.getElementById("app");
const $ = (s,r=document)=>r.querySelector(s);
const esc = s => s.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;");

function updateMeter(){
  const n = state.done.size, t = LESSONS.length;
  $("#meterTxt").textContent = `${n} من ${t} دروس`;
  $("#meterBar").style.width = (n/t*100)+"%";
}

/* ============ الصفحة الرئيسية ============ */
function renderHome(){
  state.view = "home";
  const next = LESSONS.findIndex((_,i)=>!state.done.has(i));
  let html = `
  <div class="wrap">
    <section class="hero">
      <div>
        <h1>تعلم مع سليمان</h1>
        <p class="lead">كورس بايثون كامل بالعربي: ${LESSONS.length} درساً في أربعة مستويات، كل درس فيه شرح ومثال تشغّله بنفسك وتمرين واختبار قصير. تبدأ من الصفر وتنتهي بمشروع تضعه في ملف أعمالك.</p>
        <button class="cta" id="startBtn">${state.done.size ? "أكمل من حيث توقفت" : "ابدأ الدرس الأول"}</button>
        <button class="ghost" id="mapBtn">شاهد خريطة الطريق</button>
      </div>
      <div class="demo" aria-live="polite">
        <label for="nm">اكتب اسمك وشاهد بايثون تردّ عليك</label>
        <input id="nm" value="سليمان" maxlength="24" autocomplete="off">
        <pre><span class="k">name</span> = <span class="s">"<span id="d1">سليمان</span>"</span>
<span class="k">print</span>(<span class="s">f"أهلاً يا {name}، يلا نبدأ!"</span>)</pre>
        <div class="out" id="d2">أهلاً يا سليمان، يلا نبدأ!</div>
      </div>
    </section>

    <section id="map">
      <h2 class="sec">خريطة الطريق</h2>
      <p class="sub">الدروس مرتبة، كل درس يبني على الذي قبله. اضغط على أي درس لتبدأ.</p>`;
  let n = 0;
  LEVELS.forEach(lv=>{
    html += `<div class="level"><div class="level-head"><h3>${lv.name}</h3><span>${lv.desc}</span></div><ol class="path">`;
    LESSONS.forEach((l,i)=>{
      if(l.lv!==lv.id) return;
      n++;
      const cls = state.done.has(i) ? "done" : (i===next ? "cur" : "");
      html += `<li><button class="node ${cls}" data-i="${i}" data-n="${n}"><span><span class="t">${l.title}</span><br><span class="d">${l.sum}</span></span></button></li>`;
    });
    html += `</ol></div>`;
  });
  html += `</section></div>`;
  app.innerHTML = html;

  const nm = $("#nm");
  nm.addEventListener("input",()=>{
    const v = nm.value.trim() || "صديقي";
    $("#d1").textContent = v;
    $("#d2").textContent = `أهلاً يا ${v}، يلا نبدأ!`;
  });
  $("#startBtn").onclick = ()=> openLesson(next === -1 ? 0 : next);
  $("#mapBtn").onclick = ()=> $("#map").scrollIntoView({behavior:"smooth"});
  app.querySelectorAll(".node").forEach(b=> b.onclick = ()=> openLesson(+b.dataset.i));
  updateMeter();
}

/* ============ محرر الكود ============ */
let pyPromise = null;
function loadPy(){
  if(pyPromise) return pyPromise;
  pyPromise = new Promise((res,rej)=>{
    const s = document.createElement("script");
    s.src = "https://cdn.jsdelivr.net/pyodide/v0.26.4/full/pyodide.js";
    s.onload = async()=>{ try{ res(await loadPyodide()); }catch(e){ pyPromise=null; rej(e);} };
    s.onerror = ()=>{ pyPromise=null; rej(new Error("load")); };
    document.head.appendChild(s);
  });
  return pyPromise;
}

function makeEditor(code){
  const box = document.createElement("div");
  box.className = "editor";
  box.innerHTML = `<textarea spellcheck="false" aria-label="محرر الكود"></textarea>
    <div class="bar"><button class="run">▶ شغّل</button><button class="mini reset">إعادة</button><button class="mini copy">نسخ</button><span class="status"></span></div>
    <pre class="output" aria-live="polite"></pre>`;
  const ta = $("textarea",box), out = $(".output",box), st = $(".status",box);
  ta.value = code;
  ta.rows = Math.min(16, code.split("\n").length + 1);
  ta.addEventListener("keydown",e=>{
    if(e.key==="Tab"){ e.preventDefault(); const p=ta.selectionStart; ta.setRangeText("    ",p,ta.selectionEnd,"end"); }
  });
  $(".reset",box).onclick = ()=>{ ta.value = code; out.textContent=""; };
  $(".copy",box).onclick = async()=>{ try{ await navigator.clipboard.writeText(ta.value); st.textContent="تم النسخ"; }catch{ st.textContent="انسخ يدوياً"; } setTimeout(()=>st.textContent="",1800); };
  $(".run",box).onclick = async()=>{
    out.className = "output"; out.textContent = "";
    st.textContent = "جارٍ تجهيز بايثون… (أول مرة تأخذ بضع ثوانٍ)";
    try{
      const py = await loadPy();
      let buf = "";
      py.setStdout({batched:s=>{ buf += s + "\n"; }});
      py.setStderr({batched:s=>{ buf += s + "\n"; }});
      st.textContent = "يعمل…";
      await py.runPythonAsync(ta.value);
      out.textContent = buf || "(انتهى التنفيذ بدون مخرجات)";
      st.textContent = "تم";
    }catch(e){
      out.className = "output err";
      if(e && e.message === "load"){
        out.textContent = "تعذّر تحميل مشغّل بايثون داخل هذه الصفحة. انسخ الكود وجرّبه في python.org أو Google Colab.";
        st.textContent = "";
      }else{
        out.textContent = String(e.message || e).split("\n").slice(-4).join("\n");
        st.textContent = "حدث خطأ — اقرأ الرسالة، فهي تدلّك على المشكلة";
      }
    }
  };
  return box;
}

/* ============ صفحة الدرس ============ */
function openLesson(i){
  state.view = "lesson"; state.i = i;
  const L = LESSONS[i];
  const lvName = LEVELS.find(v=>v.id===L.lv).name;
  app.innerHTML = `<div class="wrap"><article class="lesson">
    <button class="crumb" id="back">‹ خريطة الطريق</button>
    <h1>${L.title}${state.done.has(i) ? '<span class="badge-done">مكتمل</span>' : ''}</h1>
    <div class="tag">${lvName}</div>
    ${L.body}
    <section class="block"><h3>جرّب بنفسك</h3><p>الكود التالي قابل للتعديل، غيّر فيه وشغّله وشاهد النتيجة.</p><div id="ex"></div></section>
    <section class="block"><h3>تمرين</h3><div class="task"><p>${L.task}</p></div><div id="tk"></div>
      <details class="sol"><summary>اعرض الحل بعد المحاولة</summary><div id="sl"></div></details></section>
    <section class="block quiz"><h3>اختبر فهمك</h3><div id="qz"></div></section>
    <div class="nav"><button id="prev" ${i===0?"disabled":""}>الدرس السابق</button><button class="primary" id="next">${i===LESSONS.length-1?"العودة للخريطة":"الدرس التالي"}</button></div>
  </article></div>`;
  $("#ex").appendChild(makeEditor(L.code));
  $("#tk").appendChild(makeEditor(L.starter));
  $("#sl").appendChild(makeEditor(L.solution));
  renderQuiz(i);
  $("#back").onclick = renderHome;
  $("#prev").onclick = ()=> openLesson(i-1);
  $("#next").onclick = ()=> i===LESSONS.length-1 ? renderHome() : openLesson(i+1);
  window.scrollTo({top:0});
  updateMeter();
}

function renderQuiz(i){
  const L = LESSONS[i], wrap = $("#qz");
  state.answers[i] = state.answers[i] || {};
  L.quiz.forEach((q,qi)=>{
    const d = document.createElement("div"); d.className = "q";
    d.innerHTML = `<p>${esc(q.q)}</p><div class="opts"></div><div class="fb" role="status"></div>`;
    const opts = $(".opts",d), fb = $(".fb",d);
    q.o.forEach((o,oi)=>{
      const b = document.createElement("button"); b.className = "opt"; b.innerHTML = `<code>${esc(o)}</code>`;
      if(!/[A-Za-z_(\[{"'=]/.test(o)) b.innerHTML = esc(o);
      b.onclick = ()=>{
        if(oi===q.a){
          b.classList.add("right"); fb.className="fb good"; fb.textContent="إجابة صحيحة";
          opts.querySelectorAll("button").forEach(x=>x.disabled=true);
          state.answers[i][qi] = true;
          if(Object.keys(state.answers[i]).length === L.quiz.length && !state.done.has(i)){
            state.done.add(i); updateMeter();
            $(".lesson h1").insertAdjacentHTML("beforeend",'<span class="badge-done">مكتمل</span>');
          }
        }else{
          b.classList.add("wrong"); b.disabled = true; fb.className="fb no"; fb.textContent="ليست صحيحة، جرّب خياراً آخر";
        }
      };
      opts.appendChild(b);
    });
    wrap.appendChild(d);
  });
}

$("#homeBtn").onclick = renderHome;
renderHome();
</script>
</body>
</html>
