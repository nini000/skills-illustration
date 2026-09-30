---
name: "illustration-step01-brainstorm"
description: 為 Portal/Admin 的插圖情境發想「要畫什麼物件」,每個頁面產出 3 個簡短的物件 prompt 候選。使用者貼出頁面的 Placement & trigger、情境敘述,或打「Prompt brainstorming」時觸發;只要是在想某個頁面/空狀態插圖要畫什麼,即使沒說觸發詞也使用。只管概念物件,不管風格。
---

# 插圖概念發想

## 目的

每個頁面給 3 個**不同物件**的候選 prompt。
產出的 prompt 要能直接丟進產圖工具使用,細緻程度對齊下方範例:**一個物件,最多加一個限定細節**。

## 輸入

使用者通常會貼這種格式(可一次多頁):

```
Placement & trigger:
Portal - Booking 還沒有建立的 Booking
```

- 有頁面/模組名稱和觸發情境就直接發想,不追問。
- 只有在看不出是哪個模組、什麼情境時才問。

## 輸出格式

```
## Portal - [模組] [情境簡述]

**A. [中文物件名]**
> [英文 prompt]

**B. [中文物件名]**
> [英文 prompt]

**C. [中文物件名]**
> [英文 prompt]
```

- 英文 prompt 放在 `>` 引言區塊,方便單獨複製。
- 不加中文翻譯、不加解釋。只有在物件跟模組的關聯不直觀時,才在引言下補一行短說明。
- 多頁時依序輸出,不加總結。

## 三個候選的取材角度

三個候選要是**不同的物件**,不是同一物件的變形。盡量各取一個角度(不必硬湊,但避免三個都同一類):

1. **模組本體物件**:這個功能在現實中對應的東西(Notification → bell;Report → clipboard)
2. **動作/工具**:使用這個功能時的動作或工具(Announcement → megaphone;Change log → pen)
3. **貨運相關物件**:貨代業務的實體(truck、container、bill of lading、crane、map)

## Prompt 寫法

- 以名詞為主,**1 個物件 + 最多 1 個限定細節**,通常 3–15 個英文字。
- 空狀態可以用一個簡短細節帶出「空的/還沒有」,例如 "no cargo boxes in its bed"、"blank sheet"、"empty lens"。不需要每個都加,物件本身能表達就不加。
- 不寫場景敘事、不寫構圖故事。

## 硬性排除

- 不用動物、人物、擬人化物件(長眼睛/表情的物件也不行)。
- 不寫風格(顏色、線條、flat/collage/icon style 等)。風格由使用者處理。
- 畫面不含文字,不用在 prompt 裡寫 "no text"。

## 校準範例(已實際產圖使用的 prompt,細緻程度以此為準)

| Placement & trigger | Prompt |
|---|---|
| Portal - Notification 沒有跟你相關的通知 | A bell |
| Portal - Message Notification center 沒有 thread 通知 | mail box |
| Portal - Announcement 沒有建立的 Announcement | A piece of blank paper pinned to the wall / A megaphone |
| Portal - Booking 還沒有建立的 Booking | A crane hook lifting a shipping container |
| Portal - Booking Details 還沒有 Change log | quill pen / A pen writing on the paper |
| Portal - Shipment 還沒有建立資料 | A blank bill of lading document with a magnifying glass hovering over it, empty lens |
| Portal - Shipment container 沒有 events | A delivery truck parked flat, no cargo boxes in its bed / A partially unfolded paper map |
| Portal - Billing 沒有已經建立的 Billing | a paper with $ icon & a pen |
| Portal - Document 沒有已經建立的 Document | a few sheets of paper with a paper clip |
| Portal - Report 沒有已經建立的 Report | A clipboard with a blank sheet attached |

### 輸出範例

輸入:
```
Placement & trigger:
Portal - Notification 沒有跟你相關的通知
```

輸出:
```
## Portal - Notification 沒有相關通知

**A. 鈴鐺**
> A bell

**B. 靜音的手機**
> A smartphone lying face up, blank screen

**C. 空的貨運追蹤看板**
> A departure board with blank rows
```
