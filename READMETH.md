# คุณสมบัติของ TypeScript

Repository นี้นำเสนอคุณสมบัติต่าง ๆ ของ TypeScript โดยผ่านตัวอย่างและคำอธิบายที่กระชับ(อาจสั้นไป) โดยมีเป้าหมายเพื่อช่วยทบทวนความเข้าใจและให้นักพัฒนาใหม่ๆสามารถเข้าใจและใช้คุณสมบัติที่ทรงพลังของ TypeScript สำหรับการพัฒนาโปรเจ็คที่มีโค้ดที่นักพัฒนาสามารถแล้วอ่านเข้าใจและดูแลง่าย

## Table of Contents
- [Features Covered](#features-covered)
  - [1. Basic Type Annotations](#1-basic-type-annotations)
  - [2. Interfaces and Types](#2-interfaces-and-types)
  - [3. Classes and Object-Oriented Programming](#3-classes-and-object-oriented-programming)
  - [4. Generics](#4-generics)
  - [5. Advanced Types](#5-advanced-types)
  - [6. Utility Types](#6-utility-types)
  - [7. Decorators](#7-decorators)
  - [8. Modules and Namespaces](#8-modules-and-namespaces)
  - [9. Type Assertion and Type Guards](#9-type-assertion-and-type-guards)
  - [10. Enums](#10-enums)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Examples](#running-examples)

## คุณสมบัติที่ครอบคลุม

โดยประกอบไปด้วยตัวอย่างและคำอธิบายของคุณสมบัติต่อไปนี้ใน TypeScript:

### 1. การกำหนด type พื้นฐาน
- การใช้งาน `string`, `number`, `boolean` และ type พื้นฐานอื่น ๆ
- การคาดเดา type อัตโนมัติและการกำหนด type อย่างชัดเจน

### 2. interfaceและ type 
- การสร้างและขยายinterface
- การใช้งาน type alias
- ความแตกต่างระหว่าง `interface` และ `type`

### 3. การใช้ class และการเขียนโปรแกรมเชิงวัตถุ
- การประกาศ class และการสืบทอด
- ตัวปรับแต่งการเข้าถึง (`public`, `private`, `protected`)
-  class abstraction และ interface

### 4. เจเนอริก (Generics)
- การสร้าง function และ class Generics
- การใช้ข้อจำกัดใน Generics

### 5.การใช้ type แบบขั้นที่สูงขึ้น
- type ยูเนียนและอินเตอร์เซกชัน
- type ลิเทอรัลและการทำให้แคบลง
- ยูเนียน type ที่ระบุได้ (Discriminated unions)

### 6. Utility Types
- การใช้ utility types ในตัว เช่น `Partial`, `Pick`, `Omit` และ `Record`

### 7. เดคอเรเตอร์ (Decorators)
- ภาพรวมของเดคอเรเตอร์(decorators)ใน class , method และ property

### 8. โมดูลและเนมสเปซ (module & namespace)
- การนำเข้า(input) และ ส่งออกโมดูล(exportX
- namespace สำหรับการจัดระเบียบโค้ด

### 9. การยืนยันและการตรวจสอบ type (type safe)
- การใช้ `as` สำหรับการตรวจสอบยืนยัน type 
- การสร้าง type guard แบบกำหนดเองสำหรับการตรวจสอบ type ใน runtime

### 10. Enums
- การใช้งาน numeric และ string enums
- ข้อดีและข้อจำกัด

## เริ่มต้นใช้งาน

### ข้อกำหนดเบื้องต้น
เพื่อรันตัวอย่าง คุณต้องมี:
- [Node.js](https://nodejs.org/) (เวอร์ชัน 14 เป็นต้นไปหรือใหม่กว่า)
- ติดตั้ง [TypeScript](https://www.typescriptlang.org/) ไว้ในเครื่องแบบ global

### การติดตั้ง
1. ทำการโคลน repository นี้ลงบนเครื่อง:
   ```bash
   git clone https://github.com/naijamesz/typescript-features.git
   ```
2. เข้านไดเรกทอรีโปรเจกต์:
   ```bash
   cd typescript-features
   ```
3. ติดตั้ง dependencies:
   ```bash
   npm install
   ```

### การรันตัวอย่าง
คุณสามารถรันไฟล์ TypeScript ทีละไฟล์เพื่อดูตัวอย่างการทำงาน:
```bash
npx ts-node <path-to-example-file>
```

หรือคอมไพล์ไฟล์ TypeScript เป็น JavaScript แล้วรัน:
```bash
npx tsc
node <compiled-js-file>
```
