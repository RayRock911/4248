#4248
เรารวบรวมเอกสารผลิตภัณฑ์ทั้งหมดของ GitHub ไว้ในที่เดียว! ตรวจสอบเนื้อหาสำหรับ REST API , GraphQL APIและนักพัฒนา เรียนรู้เพิ่มเติมเกี่ยวกับบล็อก GitHub
GitHub เอกสาร

GitHub.com
เซิร์ฟเวอร์องค์กร 2.21
เซิร์ฟเวอร์องค์กร 2.20
เซิร์ฟเวอร์องค์กร 2.19
เซิร์ฟเวอร์องค์กร 2.18
GitHub.com ร่วมมือกับปัญหาและดึงคำขอ เสนอการเปลี่ยนแปลงการทำงานของคุณด้วยการร้องขอการดึง เกี่ยวกับคำขอดึง
เกี่ยวกับคำขอดึง
คำขอดึงช่วยให้คุณบอกคนอื่นเกี่ยวกับการเปลี่ยนแปลงที่คุณผลักไปยังสาขาในที่เก็บบน GitHub เมื่อมีการเปิดคำขอดึงคุณสามารถพูดคุยและตรวจสอบการเปลี่ยนแปลงที่อาจเกิดขึ้นกับผู้ทำงานร่วมกันและเพิ่มความมุ่งมั่นในการติดตามก่อนที่การเปลี่ยนแปลงของคุณจะถูกรวมเข้ากับสาขาพื้นฐาน

Mac
ของ windows
ลินุกซ์
ในบทความนี้
เกี่ยวกับคำขอดึง
คำขอดึงร่าง
อ่านเพิ่มเติม
เกี่ยวกับคำขอดึง
หมายเหตุ:เมื่อทำงานกับคำขอดึงให้คำนึงถึงสิ่งต่อไปนี้:

หากคุณกำลังทำงานในรูปแบบที่เก็บที่ใช้ร่วมกันเราขอแนะนำให้คุณใช้สาขาหัวข้อสำหรับคำขอดึงของคุณ ในขณะที่คุณสามารถส่งคำขอดึงจากสาขาใด ๆ หรือกระทำการด้วยสาขาหัวข้อคุณสามารถผลักดันการติดตามผลหากคุณต้องการอัปเดตการเปลี่ยนแปลงที่เสนอของคุณ
เมื่อผลักดันให้ส่งคำขอดึงอย่าบังคับให้กด การบังคับให้กดอาจทำให้คำขอถอนของคุณเสียหาย
หลังจากเริ่มต้นคำขอดึงคุณจะเห็นหน้าตรวจสอบที่แสดงภาพรวมระดับสูงของการเปลี่ยนแปลงระหว่างสาขาของคุณ (สาขาเปรียบเทียบ) และสาขาพื้นฐานของที่เก็บ คุณสามารถเพิ่มบทสรุปของการเปลี่ยนแปลงที่เสนอตรวจสอบการเปลี่ยนแปลงที่ทำโดยคอมมิทเพิ่มป้ายกำกับเหตุการณ์สำคัญและผู้รับโอนและผู้สนับสนุนหรือทีมของ @mention แต่ละคน สำหรับข้อมูลเพิ่มเติมโปรดดู " การสร้างคำขอดึง "

เมื่อคุณสร้างคำขอดึงแล้วคุณสามารถส่งข้อความยืนยันจากสาขาหัวข้อของคุณเพื่อเพิ่มคำขอลงในคำขอดึงที่มีอยู่ของคุณ การกระทำเหล่านี้จะปรากฏตามลำดับเวลาในคำขอดึงและการเปลี่ยนแปลงจะปรากฏในแท็บ "ไฟล์ที่เปลี่ยนแปลง"

ผู้มีส่วนร่วมอื่น ๆ สามารถตรวจสอบการเปลี่ยนแปลงที่เสนอของคุณเพิ่มความคิดเห็นตรวจทานมีส่วนร่วมในการอภิปรายคำขอดึงและยังเพิ่มความมุ่งมั่นที่จะดึงคำขอ

คุณสามารถดูข้อมูลเกี่ยวกับสถานะการปรับใช้ปัจจุบันของสาขาและกิจกรรมการปรับใช้ที่ผ่านมาได้ในแท็บ "การสนทนา" สำหรับข้อมูลเพิ่มเติมดูที่ "การดูกิจกรรมการปรับใช้สำหรับที่เก็บ "

หลังจากคุณพอใจกับการเปลี่ยนแปลงที่เสนอแล้วคุณสามารถรวมคำขอดึง หากคุณกำลังทำงานในโมเดลที่เก็บข้อมูลที่ใช้ร่วมกันคุณสร้างคำขอดึงและคุณหรือคนอื่นจะรวมการเปลี่ยนแปลงของคุณจากสาขาฟีเจอร์ของคุณไปยังสาขาฐานที่คุณระบุในคำขอดึงของคุณ สำหรับข้อมูลเพิ่มเติมดูที่ " การรวมคำขอดึง "

หากการตรวจสอบสถานะเป็นสิ่งจำเป็นสำหรับที่เก็บการตรวจสอบสถานะที่ต้องการจะต้องผ่านก่อนที่คุณจะสามารถรวมสาขาของคุณเข้ากับสาขาที่ได้รับการป้องกัน สำหรับข้อมูลเพิ่มเติมโปรดดู " เกี่ยวกับการตรวจสอบสถานะที่จำเป็น "

คุณสามารถเชื่อมโยงคำขอดึงกับปัญหาเพื่อแสดงว่าการแก้ไขอยู่ในความคืบหน้าและเพื่อปิดปัญหาโดยอัตโนมัติเมื่อมีคนรวมคำขอดึง สำหรับข้อมูลเพิ่มเติมโปรดดูที่ "การเชื่อมโยงคำขอดึงกับปัญหา "

เคล็ดลับ:

เพื่อสลับระหว่างการยุบและขยายทุกความคิดเห็นรีวิวล้าสมัยในคำขอดึงค้างไว้และคลิกแสดงล้าสมัยหรือซ่อนล้าสมัย สำหรับทางลัดเพิ่มเติมดูที่ " แป้นพิมพ์ลัด "option
You can squash commits when merging a pull request to gain a more streamlined view of changes. For more information, see "About pull request merges."
You can visit your dashboard to quickly find links to recently updated pull requests you're working on or subscribed to. For more information, see "About your personal dashboard."

Draft pull requests
Draft pull requests are available in public repositories with GitHub Free and GitHub Free for organizations, GitHub Pro, and legacy per-repository billing plans, and in public and private repositories with GitHub Team and GitHub Enterprise Cloud. For more information, see "GitHub's products."

When you create a pull request, you can choose to create a pull request that is ready for review or a draft pull request. Draft pull requests cannot be merged, and code owners are not automatically requested to review draft pull requests. For more information about creating a draft pull request, see "Creating a pull request" and "Creating a pull request from a fork."

When you're ready to get feedback on your pull request, you can mark your draft pull request as ready for review. Marking a pull request as ready for review will request reviews from any code owners. You can convert a pull request to a draft at any time. For more information, see "Changing the stage of a pull request."

Further reading
"Pull request" in the GitHub glossary
"About branches"
"Commenting on a pull request"
"Merging a pull request"
"Closing a pull request"
"Deleting unused branches"
"About pull request merges"
Were you able to find what you were looking for?
 Yes, easily
 Yes, eventually
 No
ความคิดเห็นเพิ่มเติม
 
Ask a human
Can't find what you're looking for?
Product
Features
Security
Enterprise
Case Studies
Pricing
Resources
Platform
Developer API
Partners
Atom
Electron
GitHub Desktop
Support
Help
Community Forum
Training
Status
ติดต่อ GitHub
บริษัท
เกี่ยวกับ
บล็อก
ร่วมงานกับเรา
กด
ร้านขายของ
© 2020 GitHub, Inc.
ข้อตกลงและเงื่อนไข
ความเป็นส่วนตัว
