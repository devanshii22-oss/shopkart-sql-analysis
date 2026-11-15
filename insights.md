# 📊 ShopKart: Key Insights

This page explains what I found in the data, in simple words. It follows the same order as my [presentation](presentation/ShopKart_Analysis.pdf).

**Data:** 14 Jan 2022 to 16 Feb 2026 | 3,238 customers | 1,669 products | 11,649 orders | 10 categories

---

## ⚡ The business in 30 seconds

| What | Number |
|---|---|
| Revenue from delivered orders | ₹44.31 Cr |
| Orders delivered | 7,745 out of 11,649 (66.5%) |
| Average delivered order | about ₹57,000 |
| Orders lost (cancelled, returned, refunded) | 1,574 (13.5%, about 1 in 7) |
| Customers who ordered more than once | 80.95% |
| Revenue from those repeat customers | 89.43% |
| Most used payment method | UPI (50%) |

---

## 1️⃣ Sales and revenue

- **Revenue is flat.** Delivered revenue was ₹10.89 Cr in 2023, ₹11.32 Cr in 2024 and ₹11.16 Cr in 2025. It went up once and then slipped a little. *(Q19)*
- **No clear busy season.** The best month was December 2024 (about ₹2.1 Cr) and the weakest full month was April 2023 (about ₹85 lakh). Most months were between ₹1.2 and ₹1.9 Cr. *(Q9, Q28)*
- **Order value is steady.** An average delivered order is worth about ₹57,000 every year. *(Q13)*

## 2️⃣ Products and categories

- **3 categories give about 90% of the revenue:** Electronics (42%), Sports & Fitness (31%) and Home & Kitchen (17%). *(Q10)*
- **One camera beats six categories.** The Whirlpool Pro3425 Camera earned ₹1.59 Cr, more than each of 6 whole categories. *(Q21)*
- **Expensive vs cheap.** The camera earned the most but sold only 47 units. The SilkenStyle Kids Fleece Pajama Set sold the most units (102) but earned only about ₹2.2 lakh. *(Q12)*
- **Grocery is stuck.** It holds about 24% of the stock but gives only 1% of the revenue. *(Q25)*
- **432 products (about 1 in 4)** have more stock than average but fewer sales than average. 16 of them never sold. *(Q17)*
- **Low stock:** 404 products (about 1 in 4) have low stock, and 2 are completely out of stock. *(Q8)*

## 3️⃣ Customers

- **Most customers come back.** 2,621 of 3,238 customers (80.95%) placed more than one order. *(Q14)*
- **Repeat customers matter most.** They bring 89.43% of the delivered revenue. One repeat customer is worth about 3.8 times a one-time customer. *(Q27)*
- **Many have gone quiet.** 93% of customers have not bought in the last 90 days. Customers here buy only once or twice a year, so this number looks high. *(Q23)*
- **Very few top customers.** Only 18 customers (0.56%) are high value, 378 are medium and 2,842 are low. *(Q24)*
- **Revenue is well spread.** The top customer gives only 0.73% of delivered revenue. *(Q22)*

## 4️⃣ Orders and payments

- **UPI is the favourite.** Half of the payments are UPI, then Card (25%), Net Banking (15%) and Cash (10%). *(Q6)*
- **1 in 7 orders is lost.** 757 were cancelled, 466 returned and 351 refunded. *(Q3)*
- **Payment method makes little difference.** Net Banking has the highest unsuccessful rate (13.85%), then Card (13.84%) and UPI (13.72%). Cash is the lowest (11.16%). *(Q15)*
- **It happens in every state.** The rate is between 12% and 15% everywhere. Punjab is the highest (15.26%) and West Bengal the lowest (12.31%). *(Q26)*

---

## 🛠️ Business problems and solutions

### Problem 1: Inventory Management
**What I saw:** Some products have a lot of stock but low sales (Grocery, 432 products). Popular products may have low stock. *(Q17, Q25)*

**Solution**
- Reduce the stock of products with low sales.
- Restock the products that sell more.
- Offer discounts on slow moving products.

### Problem 2: Customer Retention
**What I saw:** Repeat customers bring almost 90% of the revenue, but many have not bought for a long time, and few customers are high value. *(Q14, Q23, Q24, Q27)*

**Solution**
- Give special offers to inactive customers.
- Reward customers who purchase regularly.
- Send personalised offers to customers.

### Problem 3: Order and Payment Issues
**What I saw:** About 1 in 7 orders is cancelled, returned or refunded, in every state and with every payment method. *(Q3, Q6, Q15, Q26)*

**Solution**
- Find the reasons behind cancellations and refunds.
- Identify the payment methods with more failed orders.
- Improve the payment and order process.

---

## 📝 Notes about the data

- January 2022 and February 2026 are partial months, so I did not use them for growth numbers.
- I used three meanings of revenue, so the totals are different on purpose:
  - Completed payments: ₹58.57 Cr (Q2)
  - Delivered orders: about ₹44.3 Cr (Q13, Q19, Q20, Q22, Q27, Q28)
  - Price x quantity before GST, all orders: ₹65.98 Cr (Q10, Q12, Q17, Q18, Q21, Q25)
- Cancelled, Returned and Refunded orders together are called unsuccessful orders.
- This data shows what happened, not why. The solutions are ideas to test, not guaranteed fixes.
