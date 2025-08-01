##### ภูรี นาสิงคาร 6710451178 หมู่ 200
##### อชิระ จันทร์สว่าง 6710451496 หมู่ 200

[Link_DataSet](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
    - แหล่งข้อมูลโดย National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)

1. ข้อมูลมีการ/น่าจะมีการสุ่มตัวอย่างมา (sampling) แบบใด เพราะเหตุใด มีปัญหาหรือไม่ อย่างไร แก้ไขได้อย่างไร
   - คิดว่าตัวข้อมูลมีการสุ่มแบบ ```Convenience``` เพราะว่า เป็นการเก็บข้อมูลตัวอย่างที่สามารถเข้าถึงได้หรือว่ามีข้อมูลให้เก็บอยู่แล้ว
  
2. ข้อมูลมีการ/น่าจะมีการกำหนดเฉลย (labeling) ด้วยวิธีใด เพราะเหตุใด มีปัญหาหรือไม่ อย่างไร แก้ไขได้อย่างไร
    - คิดว่าตัวข้อมูลน่าจะมีการกำหนดเฉลยด้วยวิธีการ ```Hand Labels``` เพราะว่า ตัวข้อมูลยากที่จะทำให้เป็น ```Natural Labels```

3. ข้อมูลขาดความสมดุล (imbalance) หรือไม่ อย่างไร มากน้อยแค่ไหน มีปัญหาหรือไม่ อย่างไร แก้ไขได้อย่างไร
    - ไม่เพราะว่า จำนวนข้อมูลของผู้ที่เป็นโรคเบาหวานน้อยกว่าข้อมูลของผู้ที่เป็นโรคเบาหวานปานกลาง สามารถแก้ไขได้ด้วยการใช้ Oversampling ในการเพิ่มข้อมูลส่วนที่น้อย

4. จำเป็นหรือสามารถสร้างข้อมูลเพิ่ม (augmentation) ได้หรือไม่ อย่างไร
    - คิดว่าไม่ได้ครับ เพราะว่า ข้อมูลจำเป็นที่จะต้องไปเก็บมาจากตัวผู้ป่วยเองเลยคิดว่าไม่สามารถที่จะใช้หลักการ Augmentation ได้ครับ

- การมีส่วนร่วมของแต่ล่ะคนในกลุ่ม
- ภูรี ทำหน้าที่หาข้อมูลและออกแบบระบบต้นแบบ
- อชิระ ทำหน้าที่ออกแบบระบบต้นแบบและทำหน้าที่หาข้อมูล