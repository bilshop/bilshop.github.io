---
layout: default
---

# OUR MENU HERE!!!
## Strewbery Ice Cream 


![Image](https://github.com/user-attachments/assets/9f56805b-bbe7-405f-8b74-a81a6ab470bd)


### 50 บาท




<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Cool Site</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  
  <!-- Facebook Pixel Code -->
  <!-- Meta Pixel Code -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '704845828599877');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=704845828599877&ev=PageView&noscript=1"
/></noscript>
<!-- End Meta Pixel Code -->

<body>
  ...
  <script>
    fbq('track', 'Purchase', {currency: "THB", value: 50.00});
  </script>

<body>
<a href="#" class="track-purchase">BUY NOW</a>
<script>
document.querySelector('.track-purchase').addEventListener('click', function(event) {
  event.preventDefault();
  if (typeof fbq !== 'undefined') {
    fbq('track', 'Purchase', {
      currency: "USD",
      value: 30.00,
      content_name: "Strewbery Ice Cream"
    });
  }
  setTimeout(() => { window.location.href = "URL_Checkout"; }, 300);
});
</script>
</body>



[Back](./)
