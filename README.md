<meta name='viewport' content='width=device-width, initial-scale=1'/>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>पवित्र गोदारा</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #000;
      color: #fff;
      overflow-x: hidden;
    }

    .welcome-section {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      background: #000;
    }

    .welcome-text {
      font-size: 2rem;
      color: green;
      animation: rotateText 5s linear infinite;
    }

    @keyframes rotateText {
      from {
        transform: rotate(0deg);
      }
      
    }

    .profile-photo {
      margin-top: 20px;
      animation: fadeIn 3s ease-in-out;
    }

    .profile-photo img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      box-shadow: 0 10px 20px rgba(0, 255, 0, 0.7);
      animation: pulse 2s infinite alternate;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes pulse {
      from {
        transform: scale(1);
      }
      to {
        transform: scale(1.1);
      }
    }

    .content {
      margin: 50px auto;
      padding: 0 20px;
      text-align: center;
    }

    .books-section {
      margin: 50px auto;
      padding: 20px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    .books-section img {
      width: 150px;
      height: 220px;
      box-shadow: 0 10px 20px rgba(255, 255, 255, 0.7);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .books-section img:hover {
      transform: scale(1.1);
      box-shadow: 0 15px 30px rgba(0, 255, 0, 0.9);
    }

    .sections {
      margin: 50px auto;
      width: 90%;
    }

    .section {
      margin-bottom: 50px;
      padding: 30px;
      background: #111;
      border-radius: 10px;
      box-shadow: 0 10px 20px rgba(0, 255, 0, 0.5);
      transition: transform 1s ease, opacity 1s ease;
      transform: translateX(100%);
      opacity: 0;
    }

    .section:nth-child(even) {
      transform: translateX(-100%);
    }

    .section.visible {
      transform: translateX(0);
      opacity: 1;
    }

    .section .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      font-size: 1rem;
      color: #fff;
      background: green;
      border-radius: 30px;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .section .btn:hover {
      background: darkgreen;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: green;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <!-- Welcome Section -->
  <div class="welcome-section">
    <div class="welcome-text"> मैं आपका स्वागत करता हूं...</div>
    <div class="profile-photo">
      <img src="https://www.dropbox.com/scl/fi/yip9guy1ypdke514c8hzy/IMG_20240727_112341.jpg?rlkey=mlr8nf4elrumenhtljxhebb61&st=34yyi12r&dl=1" alt="Profile Photo">
    </div>
  </div>

  <!-- About Me Section -->
  <div class="content">
    <h2>About Me</h2>
    <p>पवित्र गोदारा एक उत्साही गैर-काल्पनिक लेखक हैं, जो बीकानेर, राजस्थान से हैं। वर्तमान में महाराजा गंगा सिंह विश्वविद्यालय से विज्ञान में स्नातक की पढ़ाई कर रहे हैं। पवित्र ने अपने लेखन को दूसरों को ज्ञान और अंतर्दृष्टि के माध्यम से सशक्त बनाने के लिए समर्पित किया है।</p><br>

<p>उनकी पहली किताब, *शुरुआती निवेशक*, उनके समर्पण को दर्शाती है, लेकिन उनका जीवन का लक्ष्य कई लोगों के जीवन को बदलना है। पवित्र का मानना है कि लेखन और एक अच्छे संगठन के माध्यम से वे समाज में सकारात्मक बदलाव ला सकते हैं। उनका उद्देश्य एक ऊर्जावान संगठन बनाना है, जो उन लोगों की मदद कर सके, जिन्हें इसकी आवश्यकता है।</p><br>

<p>पवित्र व्यवसाय में भी रुचि रखते हैं, जो भारत की नींव हैं और भारतीय जीडीपी में महत्वपूर्ण भूमिका निभाते हैं। वे विभिन्न प्रकार के लोगों से जुड़ने और नए अवसरों की खोज करने के लिए उत्सुक हैं। उनका मानना है कि संगठन में शक्ति है, और वे एक प्रभावशाली प्रभाव उत्पन्न करने के लिए लोगों को एक साथ जोड़ने का प्रयास कर रहे हैं।</p><br>

<p>पवित्र गोदारा का मिशन है कि वे अपने लेखन, संगठन और व्यक्तिगत प्रयासों के माध्यम से उन लोगों के जीवन में बदलाव लाएं, जिन्हें इसकी आवश्यकता है। वे एक प्रेरणादायक समुदाय बनाने के लिए तत्पर हैं, जहाँ लोग एक-दूसरे से जुड़ सकें और अपने और दूसरों के जीवन को सुधार सकें।</p>

  </div>

  <!-- Books Section -->
  <div class="books-section">
    <img src="https://www.dropbox.com/scl/fi/7pkf0wpgj795r0s30z8sv/Add-a-subheading_20240601_123621_0000.png?rlkey=nq7ayx54632rjganuxlkqrmz6&st=f45ua5gq&dl=1" alt="Frunt Page">
    <img src="https://www.dropbox.com/scl/fi/rh1zm58lvgzgrfuwvv7wp/Add-a-subheading_20240601_123621_0001.png?rlkey=0f9na60n0twa7mkiypd90snx5&st=kweh1ink&dl=1" alt="Back Page">
  </div>
  <div class="content">
    <h2>About Book</h2>
    <p><strong>शुरुआती निवेशक</strong> एक अनोखी पुस्तक है जो युवा निवेशकों के लिए निवेश के मनोवैज्ञानिक पहलुओं की गहराई में जाती है। यह पुस्तक उन कारणों को स्पष्ट करती है जिनकी वजह से सफलता के लिए नियमों का पालन करना आवश्यक है। इसमें एक युवा निवेशक की यात्रा का वर्णन किया गया है, जो विभिन्न परिस्थितियों और मनोवैज्ञानिक चुनौतियों का सामना करता है, जिससे वह कई गलतियाँ करता है।</p><br>

<p>यह पुस्तक बताती है कि कैसे एक युवा व्यक्ति अपनी संभावनाओं से समर्थन प्राप्त करता है और निवेश के क्षेत्र में सफलता की ओर बढ़ता है, लेकिन कैसे वह डर और लालच जैसे मनोवैज्ञानिक भावनात्मक कारणों के चलते अपने मार्ग से भटक जाता है।</p><br>

<p><strong>मुख्य संदेश:</strong> <em>शुरुआती निवेशक</em> का मुख्य संदेश यह है कि भावनात्मक संतुलन और मनोवैज्ञानिक समझ निवेश में सफलता प्राप्त करने के लिए आवश्यक हैं। यह पुस्तक युवा निवेशकों को अपने भावनात्मक अवरोधों को पहचानने और नियंत्रित करने की कला सिखाती है।</p><br>

<p><strong>निष्कर्ष:</strong> <em>शुरुआती निवेशक</em> एक शैक्षिक पुस्तक है जो युवा निवेशकों को उनके निवेश यात्रा में मार्गदर्शन करती है। यह पुस्तक निवेश के क्षेत्र में मानसिक और भावनात्मक चुनौतियों को प्रस्तुत करती है और सिखाती है कि कैसे इन चुनौतियों को पार करके सफलता की ओर बढ़ा जा सकता है।</p><br>

<p>क्या आप तैयार हैं अपने निवेश के सफर को एक नई दिशा देने के लिए? <em>शुरुआती निवेशक</em> के साथ जुड़ें और जानें कि कैसे आप अपने मनोवैज्ञानिक अवरोधों को पार कर सकते हैं और निवेश की दुनिया में सफलता की ओर बढ़ सकते हैं!</p>

  </div>

  <!-- Sections -->
  <div class="sections">
    <div class="section">
        <p>स्वागत है आपका <strong>Creative Minds</strong> समूह में, जहाँ हम मिलकर विचारों की नई दुनिया का निर्माण करते हैं।
<br>
<p>यह समूह विभिन्न क्षेत्रों के विशेषज्ञों, विचारकों और रचनात्मक व्यक्तियों को एक साथ लाता है।
<br>
<p>हमारा उद्देश्य है एक ऐसा मंच बनाना है, जहाँ हम अपने अनुभवों और ज्ञान को साझा कर सकें और समाज में सकारात्मक बदलाव ला सकें।
<br>
<p>हमारी गतिविधियों में कार्यशालाएँ, सेमिनार और नेटवर्किंग इवेंट्स शामिल हैं, जो सदस्यों को व्यक्तिगत और पेशेवर विकास में मदद करते हैं।
<br>
<p><strong>हमारा मुख्य उद्देश्य है विभिन्न मानसिकताओं और कौशलों वाले लोगों को जोड़ना है। हम मानते हैं कि टीमवर्क महत्वपूर्ण है। कई बार लोग कहते हैं कि वे अकेले हैं और उन्हें एक टीम की आवश्यकता है जो उनके साथ काम करे, उनकी मदद करे और कुछ अच्छा बनाए। इसलिए, क्यों नहीं हम सभी एक साथ मिलकर एक अच्छी टिम बनाएं जो एक दूसरे का व वास्तव में अपने कौशल व बुद्धिमता से समर्थन करे और अनेकों सपने साकार करे।</strong>
<br>
<p>आइए, हम सब मिलकर एक नई दिशा में कदम बढ़ाएँ और अपने विचारों से एक उज्जवल भविष्य का निर्माण करें!</p>
      <a href="https://forms.gle/wCxjgXezZja3CWWz9" target="_self" class="btn">Connect</a>
    </div>
    

    <div class="section">
      <p><strong>प्रिय पाठक,</strong><br>

<p>आपका स्वागत है! हम आपकी राय जानने के लिए उत्सुक हैं। कृपया हमारे पुस्तक <strong>"शुरुआती निवेशक"</strong> के बारे में अपने विचार साझा करें। आपकी समीक्षा न केवल हमें बेहतर बनाने में मदद करेगी, बल्कि अन्य पाठकों को भी इस पुस्तक के बारे में जानने में मदद करेगी।</p>
      <a href="https://forms.gle/9QEV3DhvszBFLBqU6" target="_self" class="btn">Book Reviwe</a>
    </div>
    <div class="section">
      
इस फॉर्म के माध्यम से आप मुझसे कोई भी सवाल, संदेह या प्रश्न पूछ सकते हैं।<br>
यदि आपके मन में कोई विचार है या आप मुझसे व्यक्तिगत रूप से जुड़ना चाहते हैं, तो कृपया इस फॉर्म का उपयोग करें।<br>
आपके संदेशों का स्वागत है, और मैं जल्द से जल्द उत्तर देने का प्रयास करूंगा!</p>

      <a href="https://forms.gle/Y5s9DEiNVT2fi3ab6" target="_self" class="btn">Connect</a>
    </div>
    <div class="section">
      <p>स्वागत है आपका <strong>पवित्रा गोदारा के ब्लॉग</strong> पर।<br>
यहाँ हम अपने समुदाय के विचारों, चर्चाओं और नवीनतम जानकारी को साझा करते हैं।<br>
हमारा उद्देश्य है आपको ऐसे विषयों पर जानकारी प्रदान करना जो आपके लिए उपयोगी और विचारशील हों।<br>
इस ब्लॉग के माध्यम से, हम सामूहिक संवाद को बढ़ावा देते हैं और आपको नए दृष्टिकोणों से अवगत कराते हैं।<br>
आइए, हमारे साथ जुड़ें और इस यात्रा का हिस्सा बनें!</p>

      <a href="https://pavitragodarablogs.blogspot.com/?m=1" target="_self" class="btn">Read</a>
    </div>
  

  <!-- Footer -->
  <footer>© All rights reserved.</footer>

  <script>
    const sections = document.querySelectorAll('.section');
    window.addEventListener('scroll', () => {
      sections.forEach(section => {
        const rect = section.getBoundingClientRect();
        if (rect.top < window.innerHeight && rect.bottom > 0) {
          section.classList.add('visible');
        } else {
          section.classList.remove('visible');
        }
      });
    });
  </script>


