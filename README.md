# DWDM21
Data Warehouse and Data Mining

นายชยากร จันทร์ลุน 623020517-9

GROP NAME I Love อ.ต้น

1 นายชยากร จันทร์ลุน 623020517-9

2 นายช่วงชัย จันทร์มณี

3 อภิวัฒน์ เหลี่ยมสิงขร

4 นวลแพร พนาวัฒนวงค์

5 กิตติคุณ เกียรติศักดิ์ศิริ

# สารบัญเนื้อหา

# สรุปเนื้อหาบทที่ 1 Introduction
- https://github.com/chayakonchanlun/DWDM21/blob/main/%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88_1_Introduction.ipynb
- ความหมายเเละนิยามของ Data Mining
- ขั้นตอนเเละองค์ประกอบของ Data Mining
- knowledge discovery (kdd) process
- Multi-Dimensional View of Data Mining


# สรุปเนื้อหาบทที่ 2 Getting to Know Your Data
- Lecture
https://github.com/chayakonchanlun/DWDM21/blob/main/%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B9%80%E0%B8%99%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%B2%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88_2_Getting_to_Know_Your_Data.ipynb

    - ขนาดของข้อมูล
    
    - คุณสมบัติของ matrix
    
    - การบันทึกข้อมูล
    
    - กราฟเเละเครือข่าย
    
    - Ordered Data
    
    - ข้อมูลเชิงพื้นที่ ภาพ เเละมัลติมีเดีย
    
    - ลักษณะสำคัญของข้อมูล
    
    - ข้อมูลที่เป็นตัวเลข
    
- Googlecolab

    - ประกอบไปด้วยส่วยย่อยดังนี้ 


    1 Basic Python 
    
      - Casting
      - Data Structure
      - Loop
      - Condition
      - Function


     2 Data Visualization https://github.com/chayakonchanlun/DWDM21/blob/main/Data_Visualization.ipynb
     
      - Scatter plot
      - Plot
      - Bar chart
      - Histogram


     3 Distance Numpy https://github.com/chayakonchanlun/DWDM21/blob/main/Distance_Numpy.ipynb
     
      - Numpy Array
      - สร้าง numpy array
      - สร้าง matrix เริ่มต้น (Zeros,ones)
      - สร้าง matrix randoom
      - matrix properties


# บทที่ 3 Data Preprocessing 
- https://github.com/chayakonchanlun/DWDM21/blob/main/Data_preposcessing_(chepter3).ipynb
- Meta Data (Data ที่ใช้อธิบาย Data)
  - ชี้ข้อมูลในตาราง
  - ชี้แบบธรรมดา (ใช้[ชื่อcolumn][index])
  - ชี้แบบ .iloc (มองข้อมูลเป็น matrix)
- Missing Values
  - Handling Missing Value 1 (ลบค่า missing)
  - Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
  - Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
  - Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
  - Handling Missing Value 4 (เเทนด้วย ค่ากลาง)
  - Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียว)
- Select data by value [PD]
  - สร้าง list ของ boolean
  - นำ list ของ boolean มาเลือกค่าในตาราง
  - ต่อตารางแนวแกน Y [PD]
  - Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน) (ต่อ)
- การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
  - Grop by (pandas)
  - [PD] save ตารางเอาไปใช้ที่อื่น
  - [PD]การสร้างตาราง

# บทที่ 4 Data Warehousing and On-line Anaalytical Processing

https://github.com/chayakonchanlun/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%204%20Data%20Warehousing%20and%20On-line%20Anaalytical%20Processing.pdf

   - Data Warehouse : Basic concepts
   - Data Warehouse Mining : Data Cube and OLAP
   - OLTP vs. OLAP
   - Data Cubes
   - Data Warehouse Disng and Usage
   - Data Warehouse Implementation

# บทที่ 5 
https://github.com/chayakonchanlun/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%205.pdf
- Googlecolab
- Association Rules https://github.com/chayakonchanlun/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb
    - Besic Concepts
    - K-itemsets 
    - ลบ records ที่ถูก cancel ออกไป
    - Plot graph of Itemsets
    - Frequence Itemsets to Association Rule
    - Efficient Pattern Mining Methods
    - Apriori
    - Support
    - 
# บทที่ 6
- ประกอบด้วย 3 ส่วนย่อย
- Desition Tree https://github.com/chayakonchanlun/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb
   - Load Data
   - Train Model
   - import(เรียกใช้ algorithm ที่เราต้องการ)
   - define (กำหนด paramiters ให้กับ model)
   - train (ฝึกสอนตัวแบบ)
   - plot tree
   - Evaluation
   - Random
   - Advanced Tree
   - import
   - Define
   - Train
   - TEST
- KNN https://github.com/chayakonchanlun/DWDM21/blob/main/Chap_7_Classification(KNN_NN).ipynb
   - Load data
   - Split Data
   - Train Model
   - import
   - knn1
   - knn2
   - knn3
   - Retrain & Evaluate
   - Neural Network
   - import
   - Define
   - Train - Test
   - ANN 2
   - ANN 3
- Evaluation https://github.com/chayakonchanlun/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb
   - Load data
   - เเบ่ง Data
   - สร้าง Model ทำนาย
   - import
   - Define
   - Train
   - Evaluation
   - 
# บทที่ 7 
- Lecture https://github.com/chayakonchanlun/DWDM21/blob/main/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%88%207.pdf
- Googlecolab https://github.com/chayakonchanlun/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb
   - K-means Generate 
   - Data Explore 
   - Data Clustering 
   - import 
   - Define 
   - Fit-Predict 
   - Exanple
