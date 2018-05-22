# SeoulLandmark
2017년 서울시 앱공모전 출품작(서울시 랜드마크)  
Google Cloud Vision API - Landmark   
https://cloud.google.com/vision

# Logo
<img src="https://user-images.githubusercontent.com/11040627/40346388-a0fc269a-5dd7-11e8-97d7-0eacc16c7f64.png"/>

# Screenshots
**1. 이미지 인식**  
<img src="https://user-images.githubusercontent.com/11040627/40346685-92e63770-5dd8-11e8-90be-ee532b2d04f0.png" width="50%"/>

**2. Request Data**
<pre><code>
{
  "landmarkAnnotations": [
    {
      "mid": "/m/02v3t6",
      "description": "Gyeongbokgung",
      "score": 0.48370042,
      "boundingPoly": {
        "vertices": [
          {
            "x": 259,
            "y": 306
          },
          {
            "x": 573,
            "y": 306
          },
          {
            "x": 573,
            "y": 417
          },
          {
            "x": 259,
            "y": 417
          }
        ]
      },
      "locations": [
        {
          "latLng": {
            "latitude": 37.570092,
            "longitude": 126.977
          }
        }
      ]
    },
    {
      "mid": "/m/02v3t6",
      ...
</code></pre>

**3. 데이터 바인딩**  
<img src="https://user-images.githubusercontent.com/11040627/40346686-9317cfa6-5dd8-11e8-88fc-9bbbb5a38c9d.png" width="50%"/>
