## 1. Intro


> **프로젝트 명 :** Lane Detection & Traffic Sign Recognition

> **프로젝트 형태 :** 대학교 전공 과목 프로젝트 / 1인 프로젝트

<br>

## 2. My Work
- 영상처리 기초 실습
![그림13](https://user-images.githubusercontent.com/68436925/108623949-2da20f80-7485-11eb-96de-9814eba449d7.png)

- 차선 검출

- 교통 신호판 분류
<br>

## 3. Project

### 🎈 차선 검출

<details>
<summary>알고리즘 순서도</summary>
  
**1. Gray Scale:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625211-02bbb980-748d-11eb-9f7a-0ed42a3cd2ac.png)

<br>

**2. Gaussian Blur:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625218-0fd8a880-748d-11eb-9690-68fbba2931ef.png)

<br>

**3. Canny Edge Detection:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625228-2121b500-748d-11eb-8474-f7657cb53fb5.png)

<br>

**4. Region of Interest:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625313-99887600-748d-11eb-855f-9a8fefb555ea.png)

<br>

**5. Hough Line Detection:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625253-3860a280-748d-11eb-9142-944823ccfcfc.png)

<br>

**6. Crossing Point Detect:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625259-431b3780-748d-11eb-89c8-ffaaa00e78a1.png)

<br>

**7. Vanishing Point Detect:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625271-54644400-748d-11eb-95a8-678d7a4018ee.png)

<br>

**8. Horizon Line Remove:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625279-5e864280-748d-11eb-9292-710395b61f3c.png)

<br>

**9. RANSAC:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625331-b45aea80-748d-11eb-946e-711da2918d4b.png)

<br>

**10. Connect Vanishing Line:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625290-6fcf4f00-748d-11eb-9352-3e7623caa0a8.png)

<br>

**11. Weighted Line:** <br>
![image](https://user-images.githubusercontent.com/68436925/108625296-7d84d480-748d-11eb-8d24-50fb892a4e30.png)

</details>

<details>
<summary>결과물</summary>
  
![](https://user-images.githubusercontent.com/68436925/108625637-57f8ca80-748f-11eb-854b-dafa2fc658a4.gif)

</details>

<br>

### 🎈 교통 신호판 분류

<details>
<summary>데이터 SET</summary>

![image](https://user-images.githubusercontent.com/68436925/108626063-a60ecd80-7491-11eb-8973-8a3996b9434e.png)

</details>

<details>
<summary>알고리즘 순서도</summary>

**1. Size Equalization:**<br>
![image](https://user-images.githubusercontent.com/68436925/108625954-005b5e80-7491-11eb-8a9b-abfb3157a21c.png)

<br>

**2. Brightness Equalization:**<br>
![image](https://user-images.githubusercontent.com/68436925/108625973-1ff28700-7491-11eb-89fb-1448f3fe1d8f.png)

<br>

**3. CNN:**<br>
![image](https://user-images.githubusercontent.com/68436925/108625990-37317480-7491-11eb-9d46-460a1506dc97.png)

<br>
</details>

<details>
<summary>결과물</summary>
  
![image](https://user-images.githubusercontent.com/68436925/108626030-752e9880-7491-11eb-8faa-509bf131f355.png)
  
</details>
