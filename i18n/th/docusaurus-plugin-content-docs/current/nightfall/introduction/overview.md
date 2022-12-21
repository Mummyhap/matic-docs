---
id: overview
title: ภาพรวม
sidebar_label: Overview
description: ภาพรวม Nightfall
keywords:
  - docs
  - polygon
  - nightfall
  - privacy
  - rollup
  - zk
image: https://matic.network/banners/matic-network-16x9.png
---

Polygon เชื่อมั่นในวิสัยทัศน์ที่เห็นบริษัทหลายแห่งมีปฏิสัมพันธ์ซึ่งกันและกันในอนาคตอันใกล้ผ่านสัญญาอัจฉริยะเพื่อดำเนินการตามตรรกะทางธุรกิจและจัดการการแลกเปลี่ยนสินค้าและบริการ

Polygon ร่วมกับ [Ernst & Young](https://blockchain.ey.com/) นำเสนอโซลูชัน Rollup Layer 2 ที่เน้นความเป็นส่วนตัวแบบสาธารณะซึ่งเรียกว่า Polygon Nightfall เพื่อเปิดใช้งานการเข้าถึงและความเป็นส่วนตัวสำหรับบริษัทที่ต้องการใช้ Ethereum

## โปรโตคอล ZK-Proof สำหรับองค์กร {#a-zk-proof-protocol-for-enterprises}

Polygon Nightfall เป็นส่วนหนึ่งของชุดโซลูชันการปรับขนาดของ Polygon ซึ่งรวมถึง[Polygon Hermez](https://polygon.technology/solutions/polygon-hermez/)[Polygon Miden](https://polygon.technology/solutions/polygon-miden/)และ [Polygon Zero](https://polygon.technology/solutions/polygon-zero/)ความแตกต่างที่สำคัญคือ Nightfall เป็นชุดรวมที่เน้นความเป็นส่วนตัวซึ่งออกแบบมาสำหรับกรณีการใช้งานขององค์กรโดยผสมผสานนวคิดของการโรลอัปในแง่ดีและการเข้ารหัส Zero-Knowledge (ZK) เพื่อเสนอธุรกรรมส่วนตัวและปรับขนาดได้

ในขณะที่ Nightfall ช่วยให้สามารถปรับขยายได้ แต่ก็มีการตั้งค่าที่จะขจัดอุปสรรคสำคัญที่บริษัทต่างๆ เผชิญอยู่ในปัจจุบันเมื่อใช้บล็อคเชน: การขาดความเป็นส่วนตัวในการทำธุรกรรมNightfall เพิ่มชั้นความเป็นส่วนตัวเพื่อไม่ให้พารามิเตอร์ธุรกรรมหลัก (เช่น มูลค่าและปลายทาง) ย้อนรอยได้คุณสมบัติทั้งสองนี้ได้ดึงความสนใจจากองค์กรเอกชนที่มองว่า Nightfall เป็นแนวทางในการดำเนินตรรกะทางธุรกิจและประสานงานกับซัพพลายเชนในเครือข่ายแบบกระจายศูนย์ในราคาที่ยั่งยืน ทั้งหมดนี้ในขณะเดียวกันก็รักษาความปลอดภัยและความเป็นส่วนตัว

## เสาของ Nightfall {#nightfall-s-pillars}

คุณค่าหลักของ Polygon Nightfall คือการเปิดใช้งานการถ่ายโอนข้อมูลที่ปลอดภัย เป็นส่วนตัว และมีค่าใช้จ่ายต่ำในเครือข่ายแบบกระจายศูนย์

![](../imgs/overview.png)

## ความเป็นส่วนตัว {#privacy}

Polygon Nightfall ใช้หลักฐาน ZK เพื่อส่งธุรกรรมส่วนตัวผู้ใช้สามารถสร้างหลักฐาน ZK ของธุรกรรมโดยไม่ต้องเปิดเผยพารามิเตอร์ธุรกรรมที่สำคัญ เช่น ปลายทางหรือมูลค่าของธุรกรรมรายละเอียดเพิ่มเติมเกี่ยวกับองค์ประกอบความเป็นส่วนตัวของ Nightfall มีอยู่ในคู่มือ[โปรโตคอล](../protocol/protocol.md)

## การรักษาความปลอดภัย {#security}

> Nightfall อยู่ระหว่างการตรวจสอบความปลอดภัย และคาดว่าจะแล้วเสร็จประมาณกลางเดือนมิถุนายน 2022เมื่อกระบวนการตรวจสอบเสร็จสิ้น ผลลัพธ์จะถูกโพสต์ที่นี่

> ในฐานะเครือข่ายใหม่ที่มีช่วงบูตสแตรป Nightfall มีมาตรการรักษาความปลอดภัยชั่วคราวเพื่อปกป้องระบบโดยมีวัตถุประสงค์เพื่อลบออกและปล่อยให้มีการกระจายศูนย์อย่างสมบูรณ์

Polygon Nightfall เป็นโครงสร้างเลเยอร์ 2 เนื่องจากใช้ประโยชน์จาก Ethereum โดยการยืมความปลอดภัยเป็นบล็อกเชนสาธารณะที่แข็งแกร่งNightfall อาศัยสมมติฐานบางประการที่รับประกันการฟื้นตัวของสินทรัพย์สมมุติฐานเหล่านี้อิงจากการตัดสินใจด้านการออกแบบและสถาปัตยกรรมหลายอย่างที่เกี่ยวข้องกับ ZK-SNARKS ซึ่งใช้การเข้ารหัสเบื้องต้นบางอย่าง เช่น แฮชและลายเซ็น
สุดท้าย Nightfall ฝังกฎการทำงานในสัญญาอัจฉริยะต่างๆ เพื่อรับประกันว่าผู้ให้บริการจะไม่บล็อกธุรกรรมของผู้ใช้และผู้ใช้สามารถถอนสินทรัพย์ของตนได้ตลอดเวลา

โดยสรุป Nightfall ตั้งสมมติฐานด้านความปลอดภัยดังต่อไปนี้:

1. สมมติฐานด้านความปลอดภัยของ Ethereum
2. สมมติฐาน Groth16 (ความรู้เกี่ยวกับสมมติฐานเลขชี้กำลัง)
3. สมมติฐานการเข้ารหัสลับบางอย่างจากพื้นฐาน เช่น แฮช (Poseidon) และลายเซ็น
4. สมมติฐานด้านความปลอดภัยของซอฟต์แวร์ที่อาศัยการออกแบบและการใช้งานที่ถูกต้อง

## ประสิทธิภาพ {#efficiency}

ผู้เสนอบล็อกรวบรวมธุรกรรมจากผู้ใช้หลายรายและแบทช์เข้าด้วยกันเป็น L2 Blockขนาดบล็อก L2 ทั่วไปมีประมาณ 32 รายการ

ค่าก๊าซที่คาดไว้สำหรับการฝาก โอน และถอนเงินคือ 9000, 1200 และ 9500ค่าใช้จ่ายนี้เกิดจากการเก็บ 574 ไบต์ของข้อมูลการโทรต่อธุรกรรม บวกกับข้อมูลการโทรที่คงที่และการคำนวณเพื่อประมวลผลบล็อก L2ค่าใช้จ่ายจะลดลงมากถึง 80% หลังจาก[EIP 4488](https://eips.ethereum.org/EIPS/eip-4488)

## การโอนที่ไม่สามารถปฏิเสธได้ {#non-deniable-transfers}

ในฐานะที่เป็นส่วนหนึ่งของหลักฐานการโอนธุรกรรม ZK Nightfall รวมถึงการเข้ารหัสลับ (ที่อยู่โทเค็น มูลค่า รหัส และซอลท์) ที่จำเป็นในการประมวลผลข้อผูกมัดที่โอนสิ่งนี้บังคับให้ผู้ใช้เข้ารหัสความลับด้วยคีย์ที่ผู้รับรู้จักเนื่องจากคีย์เป็นส่วนหนึ่งของหลักฐาน ZK ผู้รับจึงอาศัยการปฏิเสธที่สมเหตุสมผล เนื่องจากผู้ส่งสามารถพิสูจน์ได้ว่ามีการใช้คีย์เข้ารหัสที่ถูกต้อง

## การกระจายศูนย์ {#decentralization}

ผู้ตรวจสอบและ [Challengers](docs/nightfall/protocol/actors) เป็นส่วนสำคัญของ Nightfallพวกมันทำให้แน่ใจว่าธุรกรรมและบล็อก L2 ผลิตได้ทันเวลาและถูกต้องกลไกฉันทามติที่อิงตามการพิสูจน์เดิมพัน (PoS) ถูกใช้เพื่อเลือก[ผู้เสนอ](docs/nightfall/protocol/actors)รายต่อไปของเครือข่ายในทางกลับกัน ผู้ท้าชิงจะตรวจสอบการทำงานที่ถูกต้องของเครือข่ายโดยการเพิ่มความท้าทายเมื่อตรวจพบการบล็อกที่ไม่ถูกต้องและโดยการ stake ขั้นสูงไว้โดยผู้เสนอ


## ข้อพิสูจน์ในอนาคต {#future-proof}
ด้วยความยืดหยุ่นจากการนำ Nightfall ไปใช้แบบ Optimistic จึงสามารถรวมธุรกรรมใหม่ได้ในอนาคตโดยไม่กระทบต่อธุรกรรมที่มีอยู่โดยเพียงแค่กำหนดและลงทะเบียนประเภทวงจรใหม่ที่ใช้ธุรกรรมใน ZK

## แหล่งอ้างอิง {#references}

1. [แนวทางหลายด้านในการปรับขนาด ZK](https://messari.io/article/polygon-a-multi-sided-approach-to-zk-scaling)
2. [มุมมองของ Paul's Brody ใน Nightfall](https://www.linkedin.com/pulse/say-hello-nightfall-paul-brody-1f/)