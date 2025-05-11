---<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ثراء - الثقافة العمانية</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <div id="app">
        <!-- الشاشة الرئيسية -->
        <div id="home-screen" class="screen active">
            <header>
                <h1>ثراء - الثقافة العمانية</h1>
            </header>
            <main>
                <section class="intro">
                    <img src="blob:https://web.whatsapp.com/0aa31d2a-d02c-4882-a6a2-560bead0b0b4" alt="ثراء">
                    <h2>سلطنة عمان: جوهرة التراث العربي</h2>
                    <p>
                        عمان، أرض التاريخ العريق والثقافة الأصيلة، تمتد جذور حضارتها لأكثر من خمسة آلاف سنة.
                        تتميز السلطنة بتنوع جغرافي وثقافي فريد، حيث تلتقي الصحاري الذهبية مع الجبال الشامخة
                        والبحار الزرقاء. حفظ العمانيون تراثهم الغني عبر الأجيال، من فنون العمارة التقليدية
                        إلى المنسوجات والمجوهرات والأزياء والموسيقى الشعبية، مما يجعلها وجهة ثقافية فريدة
                        في العالم العربي.
                    </p>
                </section>
                
                <div class="buttons-container">
                    <button class="theme-btn" onclick="showScreen('clothing')">
                        <i class="fas fa-tshirt"></i> اللباس العماني
                    </button>
                    <button class="theme-btn" onclick="showScreen('architecture')">
                        <i class="fas fa-archway"></i> الفنون المعمارية
                    </button>
                    <button class="theme-btn" onclick="showScreen('cuisine')">
                        <i class="fas fa-utensils"></i> الأطعمة العمانية
                    </button>
                    <button class="theme-btn" onclick="showScreen('music')">
                        <i class="fas fa-music"></i> الفنون الموسيقية الشعبية
                    </button>
                    <button class="theme-btn" onclick="showScreen('landmarks')">
                        <i class="fas fa-landmark"></i> المعالم التراثية
                    </button>
                    <button class="theme-btn" onclick="showScreen('ai-chat')">
                        <i class="fas fa-robot"></i> الشيخ سعيد
                    </button>
                    <button class="theme-btn" onclick="showScreen('vision')">
                        <i class="fas fa-chart-line"></i> رؤية عمان 2040
                    </button>
                    <button class="theme-btn" onclick="showScreen('settings')">
                        <i class="fas fa-cog"></i> الإعدادات
                    </button>
                </div>
            </main>
        </div>

        <!-- شاشة اللباس العماني -->
        <div id="clothing-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>اللباس العماني</h1>
            </header>
            <main>
                <div class="content-card">
                    <h2>الأزياء التقليدية العمانية تعكس تاريخ البلاد وثقافتها الغنية:</h2>
                    <div class="info-item">
                        <h3><i class="fas fa-male"></i> الرجال:</h3>
                        <p>يشمل الدشداشة البيضاء مع الكمة (القلنسوة) والمصار (السيف التقليدي) والعصا.</p>
                    </div>
                    <div class="info-item">
                        <h3><i class="fas fa-female"></i> النساء:</h3>
                        <p>تلبس العمانيات الثوب المزين بالخيوط الذهبية والفضية مع اللحاف (غطاء الرأس) والحلي التقليدية.</p>
                    </div>
                    <div class="image-placeholder">
                        <img src="images/omani_clothing.jpg" alt="blob:https://web.whatsapp.com/9c6e4338-81e9-49df-9897-cd9b1a23ac3f">
                    </div>
                    <p class="note">تختلف التفاصيل حسب المنطقة، حيث تتميز كل منطقة بلمساتها الخاصة على الأزياء التقليدية. 
                         النقية مع الكمة (القلنسوة التقليدية)، فيما تُكمل الزي المصار (السيف العُماني) والعصا أناقة المظهر. أما النساء، فيشتهرن بثياب العباءة المطرزة بخيوط الذهب والفضة، مع اللحاف (غطاء الرأس) المصنوع من أنسجة فاخرة، بالإضافة إلى الحلي التقليدية مثل الأساور والخواتم الفضية. تختلف التفاصيل بين المناطق، حيث تُظهر كل منطقة لمساتها الخاصة في الألوان والتطريز، مما يجعل اللباس العُماني تحفة ثقافية تروي تاريخ عُمان العريق. 🇴🇲✨


                    </p>
                </div>
            </main>
        </div>

        <!-- شاشة الفنون المعمارية -->
        <div id="architecture-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>الفنون المعمارية العمانية</h1>
            </header>
            <main>
                <div class="content-card">
                    <h2>العمارة العمانية: انسجام بين الوظيفة والجمال</h2>
                    <p>تتميز العمارة العمانية التقليدية بالخصائص التالية: </p>
                    <ul class="bullet-list">
                        <li>استخدام المواد المحلية مثل الحجر والطين والجص</li>
                        <li>النوافذ والأبواب المنقوشة بدقة</li>
                        <li>الأبراج الدفاعية في القلاع والحصون</li>
                        <li>أنظمة التبريد الطبيعية مثل المشربية والملاقف</li>
                    </ul>
                    <div class="blob:https://web.whatsapp.com/e803b5e3-3694-4f35-9152-282b7f9f3a82">
                        <img src="images/omani_architecture.jpg" alt="العمارة العمانية">
                    </div>
                    <p class="note">أشهر الأمثلة: قلعة نزوى، حصن جبرين، بيت الزبير في مسقط</p>
                </div>
            </main>
        </div>

        <!-- شاشة الأطعمة العمانية -->
        <div id="cuisine-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>الأطعمة العمانية</h1>
            </header>
            <main>
                <div class="content-card">
                    <h2>المطبخ العماني: نكهات أصيلة من أرض اللبان</h2>
                    <div class="food-item">
                        <h3><i class="fas fa-utensil-spoon"></i> الشواء</h3>
                        <p>لحم مشوي مع الأرز العماني والتوابل الخاصة</p>
                    </div>
                    <div class="food-item">
                        <h3><i class="fas fa-drumstick-bite"></i> المكبس</h3>
                        <p>لحم أو دجاج مطهو مع الأرز والبهارات في قدر حجري</p>
                    </div>
                    <div class="food-item">
                        <h3><i class="fas fa-candy-cane"></i> حلوى النخلة</h3>
                        <p>حلوى تقليدية من التمر والدقيق والسمن</p>
                    </div>
                    <div class="food-item">
                        <h3><i class="fas fa-bread-slice"></i> الهريس</h3>
                        <p>طبق من القمح واللحم المطبوخ لساعات طويلة</p>
                    </div>
                    <div class="image-placeholder">
                        <img src="blob:https://web.whatsapp.com/7243b04b-8571-4a17-a4ed-357e83451259" alt="الأطعمة العمانية">
                    </div>
                    <p class="note">يتميز المطبخ العماني باستخدام التوابل مثل الهيل والكركم والزعفران.</p>
                </div>
            </main>
        </div>

        <!-- شاشة الفنون الموسيقية الشعبية -->
        <div id="music-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>الفنون الموسيقية الشعبية</h1>
            </header>
            <main>
                <div class="content-card">
                    <h2>الموسيقى العمانية: إيقاعات من التاريخ</h2>
                    <div class="music-item">
                        <h3><i class="fas fa-drum"></i> الرزحة</h3>
                        <p>فن حربي يؤدى بالسيف والترديد الجماعي</p>
                    </div>
                    <div class="music-item">
                        <h3><i class="fas fa-microphone"></i> العازي</h3>
                        <p>فن شعبي يلقى فيه الشاعر قصيدة ويردد الحضور</p>
                    </div>
                    <div class="music-item">
                        <h3><i class="fas fa-horse"></i> التغرودة</h3>
                        <p>غناء إيقاعي يصاحبه الرقص على ظهور الخيل</p>
                    </div>
                    <div class="music-item">
                        <h3><i class="fas fa-users"></i> الميدان</h3>
                        <p>فن غنائي راقص يؤدى في المناسبات</p>
                    </div>
                    <div class="image-placeholder">
                        <img src="blob:https://web.whatsapp.com/e0ef23b5-6a21-4c3d-a191-7147687dfa30" alt="الموسيقى العمانية">
                    </div>
                    <p class="note">تستخدم الآلات التقليدية مثل العود والربابة والطبول في العزف.</p>
                </div>
            </main>
        </div>

        <!-- شاشة المعالم التراثية -->
        <div id="landmarks-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>المعالم التراثية</h1>
            </header>
            <main>
                <div class="landmarks-container">
                    <div class="landmark-card">
                        <div class="landmark-image">
                            <img src="images/nizwa_fort.jpg" alt="قلعة نزوى">
                        </div>
                        <div class="landmark-info">
                            <h3>قلعة نزوى</h3>
                            <p><i class="fas fa-map-marker-alt"></i> نزوى</p>
                            <p>قلعة تاريخية تعود للقرن الـ17، تتميز ببرجها الدائري الضخم</p>
                            <button class="map-btn" onclick="openMap('nizwa_fort')">
                                <i class="fas fa-map"></i> عرض على الخريطة
                            </button>
                        </div>
                    </div>

                    <div class="landmark-card">
                        <div class="landmark-image">
                            <img src="images/jabrin_fort.jpg" alt="حصن جبرين">
                        </div>
                        <div class="landmark-info">
                            <h3>حصن جبرين</h3>
                            <p><i class="fas fa-map-marker-alt"></i> بهلاء</p>
                            <p>تحفة معمارية تعود للقرن الـ17 تحتوي على زخارف ونقوش فنية رائعة</p>
                            <button class="map-btn" onclick="openMap('jabrin_fort')">
                                <i class="fas fa-map"></i> عرض على الخريطة
                            </button>
                        </div>
                    </div>

                    <div class="landmark-card">
                        <div class="landmark-image">
                            <img src="images/mutrah_souq.jpg" alt="سوق مطرح">
                        </div>
                        <div class="landmark-info">
                            <h3>سوق مطرح</h3>
                            <p><i class="fas fa-map-marker-alt"></i> مسقط</p>
                            <p>سوق تقليدي يعود تاريخه لمئات السنين، مشهور باللبان والعطور والحرف اليدوية</p>
                            <button class="map-btn" onclick="openMap('mutrah_souq')">
                                <i class="fas fa-map"></i> عرض على الخريطة
                            </button>
                        </div>
                    </div>

                    <div class="landmark-card">
                        <div class="landmark-image">
                            <img src="images/al_baleed.jpg" alt="مدينة البليد الأثرية">
                        </div>
                        <div class="landmark-info">
                            <h3>مدينة البليد الأثرية</h3>
                            <p><i class="fas fa-map-marker-alt"></i> صلالة</p>
                            <p>موقع تراثي عالمي كان ميناءً مهماً لتجارة اللبان في العصور الوسطى</p>
                            <button class="map-btn" onclick="openMap('al_baleed')">
                                <i class="fas fa-map"></i> عرض على الخريطة
                            </button>
                        </div>
                    </div>
                </div>
            </main>
        </div>

        <!-- شاشة الشيخ سعيد (الذكاء الاصطناعي) -->
        <div id="ai-chat-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>الشيخ سعيد - مساعد الثقافة العمانية</h1>
            </header>
            <main>
                <div class="https://poe.com/botsheikh.saaid_oman">
                    <div id="chat-messages" class="chat-messages">
                        <div class="message bot-message">
                            <div class="avatar">
                                <i class="fas fa-robot"></i>
                            </div>
                            <div class="message-content">
                                <p>مرحباً! أنا الشيخ سعيد، كيف يمكنني مساعدتك في معرفة المزيد عن الثقافة العمانية اليوم؟</p>
                            </div>
                        </div>
                    </div>
                    <div class="chat-input">
                        <input type="text" id="user-input" placeholder="اطرح سؤالاً عن الثقافة العمانية...">
                        <button id="send-btn" onclick="sendMessage()"><i class="fas fa-paper-plane"></i></button>
                    </div>
                </div>
            </main>
        </div>

        <!-- شاشة رؤية عمان 2040 -->
        <div id="vision-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>رؤية عمان 2040</h1>
            </header>
            <main>
                <div class="content-card">
                    <h2>رؤية عمان 2040: نحو مستقبل مستدام</h2>
                    <p>
                        رؤية عُمان 2040 هي خطة استراتيجية شاملة تهدف إلى تحقيق التنمية المستدامة للسلطنة،
                        وترتكز على ثلاث ركائز رئيسية:
                    </p>
                    
                    <div class="vision-point">
                        <h3><i class="fas fa-user"></i> الإنسان والمجتمع</h3>
                        <p>تنمية الموارد البشرية وبناء مجتمع مبدع ومنتج.</p>
                    </div>
                    
                    <div class="vision-point">
                        <h3><i class="fas fa-chart-line"></i> الاقتصاد والتنمية</h3>
                        <p>تحقيق تنمية اقتصادية مستدامة قائمة على الابتكار والتنوع.</p>
                    </div>
                    
                    <div class="vision-point">
                        <h3><i class="fas fa-building"></i> الحوكمة والأداء المؤسسي</h3>
                        <p>تعزيز الحوكمة الرشيدة والكفاءة المؤسسية.</p>
                    </div>
                    
                    <h3>أبرز الأهداف:</h3>
                    <ul class="bullet-list">
                        <li>تحقيق نمو اقتصادي مستدام ومتنوع</li>
                        <li>تعزيز ريادة الأعمال والابتكار</li>
                        <li>الحفاظ على الهوية العمانية والتراث الثقافي</li>
                        <li>تحسين جودة الحياة للمواطنين</li>
                        <li>تعزيز الاستدامة البيئية</li>
                    </ul>
                    
                    <h3>في المجال الثقافي، تهدف الرؤية إلى:</h3>
                    <ul class="bullet-list">
                        <li>الحفاظ على التراث الثقافي العماني وتعزيزه</li>
                        <li>دعم الصناعات الثقافية والإبداعية</li>
                        <li>تعزيز السياحة الثقافية</li>
                        <li>تسجيل المزيد من المواقع العمانية في قوائم التراث العالمي</li>
                    </ul>
                    
                    <div class="image-placeholder">
                        <img src="blob:https://web.whatsapp.com/5a090c10-e808-43a2-986f-6f3eb10175cc" alt="رؤية عمان 2040">
                    </div>
                </div>
            </main>
        </div>

        <!-- شاشة الإعدادات -->
        <div id="settings-screen" class="screen">
            <header>
                <button class="back-btn" onclick="showScreen('home')"><i class="fas fa-arrow-left"></i></button>
                <h1>الإعدادات</h1>
            </header>
            <main>
                <div class="content-card">
                    <div class="setting-item">
                        <label for="language-select">اللغة</label>
                        <select id="language-select">
                            <option value="ar">العربية</option>
                            <option value="en">English</option>
                            <option value="fr">Français</option>
                            <option value="sp">espanol</option>
                            <option value="jp">japanese</option>
                            <option value="ch">chinese</option>
                            <option value="kor">korean</option>
                            <option value="por">portuguese</option>
                            <option value="hn">hindi</option>
                        </select>
                    </div>
                    
                    <div class="setting-item">
                        <label>لون الأزرار</label>
                        <input type="color" id="btn-color" value="#4285f4">
                    </div>
                        <input type="color" id="btn-color" value="#37db89">
                    </div>
                        <input type="color" id="btn-color" value="#bf2e33">
                    </div>
                    
                    <div class="setting-item">
                        <label>لون الخلفية</label>
                        <input type="color" id="bg-color" value="#ffffff">
                    </div>
                         <input type="color" id="bg-color" value="#3b5e28">
                    </div>
                         <input type="color" id="bg-color" value="#8a4b27">
                    </div>
                         <input type="color" id="bg-color" value="#27538a">
                    </div>

                    
                    <div class="setting-item">
                        <label>حجم الخط</label>
                        <select id="font-size">
                            <option value="small">صغير</option>
                            <option value="medium" selected>متوسط</option>
                            <option value="large">كبير</option>
                        </select>
                    </div>
                    
                    <button class="save-btn" onclick="saveSettings()">حفظ الإعدادات</button>
                </div>
            </main>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
/* التنسيقات العامة */
:root {
    --primary-color: #4285f4;
    --secondary-color: #34a853;
    --text-color: #333;
    --bg-color: #fff;
    --card-bg: #f9f9f9;
    --font-family: 'Tajawal', sans-serif;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-family);
    color: var(--text-color);
    background-color: var(--bg-color);
    direction: rtl;
    line-height: 1.6;
}

#app {
    max-width: 100%;
    overflow-x: hidden;
}

.screen {
    display: none;
    width: 100%;
    min-height: 100vh;
    padding: 0;
}

.screen.active {
    display: block;
}

/* تنسيقات الهيدر */
header {
    background-color: var(--primary-color);
    color: white;
    padding: 15px 20px;
    text-align: center;
    position: relative;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

header h1 {
    font-size: 1.5rem;
    margin: 0;
}

.back-btn {
    position: absolute;
    right: 15px;
    top: 50%;
    transform: translateY(-50%);
    background: none;
    border: none;
    color: white;
    font-size: 1.2rem;
    cursor: pointer;
}

/* تنسيقات المحتوى الرئيسي */
main {
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
}

.intro {
    margin-bottom: 30px;
    text-align: center;
}

.intro h2 {
    color: var(--primary-color);
    margin-bottom: 15px;
    font-size: 1.5rem;
}

.intro p {
    text-align: justify;
    margin-bottom: 20px;
}

.intro img {
    max-width: 100%;
    border-radius: 8px;
    margin-bottom: 15px;
}

/* تنسيقات الأزرار */
.buttons-container {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.theme-btn {
    background-color: var(--primary-color);
    color: white;
    border: none;
    padding: 15px;
    border-radius: 8px;
    font-size: 1.1rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: all 0.3s ease;
    width: 100%;
}

.theme-btn:hover {
    background-color: #3367d6;
    transform: translateY(-2px);
}

.theme-btn i {
    font-size: 1.2rem;
}

/* تنسيقات بطاقات المحتوى */
.content-card {
    background-color: var(--card-bg);
    border-radius: 10px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.content-card h2 {
    color: var(--primary-color);
    margin-bottom: 15px;
    font-size: 1.3rem;
}

/* تنسيقات العناصر المعلوماتية */
.info-item, .food-item, .music-item {
    margin-bottom: 15px;
}

.info-item h3, .food-item h3, .music-item h3 {
    color: var(--secondary-color);
    margin-bottom: 5px;
    display: flex;
    align-items: center;
    gap: 8px;
}

/* تنسيقات القوائم النقطية */
.bullet-list {
    list-style-type: none;
    padding-right: 20px;
}

.bullet-list li {
    margin-bottom: 8px;
    position: relative;
    padding-right: 20px;
}

.bullet-list li:before {
    content: "•";
    position: absolute;
    right: 0;
    color: var(--primary-color);
}

/* تنسيقات الصور */
.image-placeholder {
    margin: 20px 0;
    text-align: center;
}

.image-placeholder img {
    max-width: 100%;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
}

.note {
    font-style: italic;
    color: #666;
    text-align: center;
    margin-top: 10px;
}

/* تنسيقات المعالم التراثية */
.landmarks-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.landmark-card {
    background-color: var(--card-bg);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
}

.landmark-image {
    height: 200px;
    overflow: hidden;
}

.landmark-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.landmark-info {
    padding: 15px;
}

.landmark-info h3 {
    color: var(--primary-color);
    margin-bottom: 5px;
}

.landmark-info p {
    margin-bottom: 10px;
    color: #555;
}

.landmark-info p i {
    margin-left: 5px;
}

.map-btn {
    background-color: var(--secondary-color);
    color: white;
    border: none;
    padding: 8px 15px;
    border-radius: 5px;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 5px;
    margin-top: 10px;
}

.map-btn i {
    font-size: 0.9rem;
}

/* تنسيقات الدردشة */
.chat-container {
    display: flex;
    flex-direction: column;
    height: calc(100vh - 120px);
}

.chat-messages {
    flex: 1;
    overflow-y: auto;
    padding: 15px;
    background-color: #f5f5f5;
    border-radius: 8px;
    margin-bottom: 15px;
}

.message {
    display: flex;
    margin-bottom: 15px;
}

.bot-message {
    justify-content: flex-start;
}

.user-message {
    justify-content: flex-end;
}

.avatar {
    width: 40px;
    height: 40px;
    background-color: var(--primary-color);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-left: 10px;
}

.message-content {
    max-width: 70%;
}

.message-content p {
    background-color: white;
    padding: 10px 15px;
    border-radius: 18px;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
}

.bot-message .message-content p {
    background-color: var(--primary-color);
    color: white;
    border-top-right-radius: 0;
}

.user-message .message-content p {
    background-color: #e0e0e0;
    border-top-left-radius: 0;
}

.chat-input {
    display: flex;
    gap: 10px;
}

.chat-input input {
    flex: 1;
    padding: 12px 15px;
    border: 1px solid #ddd;
    border-radius: 25px;
    font-size: 1rem;
}

.chat-input button {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: none;
    background-color: var(--primary-color);
    color: white;
    cursor: pointer;
    font-size: 1.2rem;
}

/* تنسيقات رؤية عمان 2040 */
.vision-point {
    background-color: rgba(66, 133, 244, 0.1);
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 15px;
}

.vision-point h3 {
    color: var(--primary-color);
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    gap: 8px;
}

/* تنسيقات الإعدادات */
.setting-item {
    margin-bottom: 20px;
}

.setting-item label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
    color: var(--primary-color);
}

.setting-item select, .setting-item input[type="color"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: var(--font-family);
}

.setting-item input[type="color"] {
    height: 50px;
    padding: 5px;
}

.save-btn {
    background-color: var(--primary-color);
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    width: 100%;
    margin-top: 20px;
}

.save-btn:hover {
    background-color: #3367d6;
}

/* تنسيقات الخطوط المختلفة */
.font-small {
    font-size: 0.9rem;
}

.font-medium {
    font-size: 1rem;
}

.font-large {
    font-size: 1.1rem;
}

/* التعديلات للشاشات الصغيرة */
@media (max-width: 600px) {
    header h1 {
        font-size: 1.2rem;
    }
    
    .theme-btn {
        padding: 12px;
        font-size: 1rem;
    }
    
    .content-card {
        padding: 15px;
    }
    
    .landmark-info h3 {
        font-size: 1rem;
    }
}
// إدارة شاشات التطبيق
function showScreen(screenId) {
    // إخفاء كل الشاشات
    document.querySelectorAll('.screen').forEach(screen => {
        screen.classList.remove('active');
    });
    
    // إظهار الشاشة المطلوبة
    document.getElementById(`${screenId}-screen`).classList.add('active');
    
    // إذا كانت شاشة الدردشة، قم بالتمرير إلى الأسفل
    if (screenId === 'ai-chat') {
        setTimeout(() => {
            const chatMessages = document.getElementById('chat-messages');
            chatMessages.scrollTop = chatMessages.scrollHeight;
        }, 100);
    }
}

// الدردشة مع الذكاء الاصطناعي (الشيخ سعيد)
function sendMessage() {
    const userInput = document.getElementById('user-input');
    const message = userInput.value.trim();
    
    if (message === '') return;
    
    // إضافة رسالة المستخدم
    addMessage(message, 'user');
    userInput.value = '';
    
    // محاكاة رد الذكاء الاصطناعي بعد تأخير
    setTimeout(() => {
        const response = getAIResponse(message);
        addMessage(response, 'bot');
    }, 1000);
}

function addMessage(text, sender) {
    const chatMessages = document.getElementById('chat-messages');
    
    const messageDiv = document.createElement('div');
    messageDiv.className = `message ${sender}-message`;
    
    const avatarDiv = document.createElement('div');
    avatarDiv.className = 'avatar';
    avatarDiv.innerHTML = sender === 'bot' ? '<i class="fas fa-robot"></i>' : '<i class="fas fa-user"></i>';
    
    const contentDiv = document.createElement('div');
    contentDiv.className = 'message-content';
    
    const textP = document.createElement('p');
    textP.textContent = text;
    
    contentDiv.appendChild(textP);
    messageDiv.appendChild(avatarDiv);
    messageDiv.appendChild(contentDiv);
    
    chatMessages.appendChild(messageDiv);
    
    // التمرير التلقائي لأحدث رسالة
    chatMessages.scrollTop = chatMessages.scrollHeight;
}

// ردود الذكاء الاصطناعي المبرمجة مسبقًا
function getAIResponse(query) {
    query = query.toLowerCase();
    
    // ردود مخصصة لكل فئة
    const responses = {
        'لباس': 'اللباس العماني التقليدي يشمل:<br>- الدشداشة البيضاء مع الكمة للرجال<br>- الثوب المطرز بالذهب والفضة للنساء<br>- تختلف التفاصيل حسب المنطقة!',
        'طعام': 'الأكلات العمانية الشهيرة:<br>- الشواء<br>- المكبس<br>- الهريس<br>- حلوى النخلة<br>تستخدم بهارات مميزة مثل الهيل والكركم.',
        'معمار': 'العمارة العمانية تتميز بـ:<br>- القلاع والحصون (مثل قلعة نزوى)<br>- الملاقف للتبريد الطبيعي<br>- المشربيات الخشبية المنقوشة',
        'موسيقى': 'الفنون الموسيقية العمانية:<br>- الرزحة (فن حربي)<br>- العازي (إلقاء شعر)<br>- التغرودة (غناء مع ركوب الخيل)',
        'رؤية': 'رؤية عمان 2040 تهدف إلى:<br>- التنمية المستدامة<br>- الحفاظ على التراث<br>- تعزيز الاقتصاد المعرفي',
        'default': 'أهلاً! أنا الشيخ سعيد، مساعدك للثقافة العمانية. اسألني عن:<br>- اللباس<br>- الأكلات<br>- المعالم<br>- الفنون<br>- الرؤية 2040'
    };

    // تحديد الرد المناسب
    if (query.includes('لباس') || query.includes('ملابس')) {
        return responses['لباس'];
    } else if (query.includes('طعام') || query.includes('أكل')) {
        return responses['طعام'];
    } else if (query.includes('معمار') || query.includes('بناء')) {
        return responses['معمار'];
    } else if (query.includes('موسيقى') || query.includes('غناء')) {
        return responses['موسيقى'];
    } else if (query.includes('رؤية') || query.includes('2040')) {
        return responses['رؤية'];
    } else {
        return responses['default'];
    }
}

// فتح الخريطة للمعالم التراثية
function openMap(landmarkId) {
    const landmarks = {
        'nizwa_fort': 'https://goo.gl/maps/3JkQZ9jK9XmJ7YJQ8',
        'jabrin_fort': 'https://goo.gl/maps/5h1Z8jK9XmJ7YJQ8',
        'mutrah_souq': 'https://goo.gl/maps/9k1Z8jK9XmJ7YJQ8',
        'al_baleed': 'https://goo.gl/maps/2h1Z8jK9XmJ7YJQ8'
    };
    
    if (landmarks[landmarkId]) {
        window.open(landmarks[landmarkId], '_blank');
    } else {
        alert('الخريطة غير متوفرة لهذا الموقع حالياً');
    }
}

// إدارة الإعدادات
function saveSettings() {
    const language = document.getElementById('language-select').value;
    const btnColor = document.getElementById('btn-color').value;
    const bgColor = document.getElementById('bg-color').value;
    const fontSize = document.getElementById('font-size').value;
    
    // تطبيق التغييرات
    document.documentElement.style.setProperty('--primary-color', btnColor);
    document.documentElement.style.setProperty('--bg-color', bgColor);
    
    // تغيير حجم الخط
    document.body.classList.remove('font-small', 'font-medium', 'font-large');
    document.body.classList.add(`font-${fontSize}`);
    
    // إظهار تنبيه
    alert('تم حفظ الإعدادات بنجاح!');
}

// تهيئة التطبيق عند التحميل
window.onload = function() {
    // تفعيل الشاشة الرئيسية
    showScreen('home');
    
    // تفعيل إرسال الرسالة عند الضغط على Enter
    document.getElementById('user-input').addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
            sendMessage();
        }
    });
    
    // تحميل الإعدادات المحفوظة (إن وجدت)
    if (localStorage.getItem('settings')) {
        const settings = JSON.parse(localStorage.getItem('settings'));
        document.getElementById('language-select').value = settings.language;
        document.getElementById('btn-color').value = settings.btnColor;
        document.getElementById('bg-color').value = settings.bgColor;
        document.getElementById('font-size').value = settings.fontSize;
        saveSettings(); // تطبيق التغييرات
    }
};
