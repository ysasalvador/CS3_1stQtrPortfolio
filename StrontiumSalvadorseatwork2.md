# Seatwork#2: CSS Position and z-index

**Name:** Sophia Ysabelle F. Salvador  
**Date:** March 29, 2026  

---

## Step 1 (Static vs Relative)

**Answer:**  
When I added `position: relative`, the sidebar moved from its original position based on the top and left values. Unlike static, it can now be adjusted but still stays in the normal flow of the page.

---

## Step 2 (Fixed)

**Answer:**  
When I scroll, the footer stays at the bottom of the screen and doesn’t move. This is because fixed positioning is based on the screen, not the page layout.

---

## Step 3 (Absolute)

**Answer:**  
The content moves to a specific location using top and left. It is removed from the normal flow. It is different from fixed because it depends on its parent, not the screen.

---

## Step 4 (z-index)

**Answer:**  
The notice appears on top because it has a higher z-index. If I swap the values, the content will appear on top instead.

---

## Challenge

**Answer:**
1. Set `.content` to relative and `.notice` to absolute, then use `top: 0` and `right: 0` so it stays at the top-right corner of the content.
2. If it is relative, it stays in place but can move slightly. If it is fixed, it stays on the screen even when scrolling.
3. z-index controls which element is on top. Higher value means it appears in front.

---

## Reflection

**Answer:**

a. 
- Static is the default and cannot be moved.
- Relative can move from its original position.
- Absolute is positioned based on its parent and removed from the normal flow.
- Fixed stays in one place on the screen even when scrolling.

b. 
- It uses the nearest parent with a position. If none, it uses the whole page.

c. 
- Fixed always stays in one place.
- Sticky scrolls normally first, then sticks when you reach a certain point.

d. 
- I can use fixed for a navigation bar so it stays visible.
- Use absolute for buttons like “Register Now” on banners.
- Use z-index so announcements appear on top.
- Use sticky for headers so they stay visible when scrolling.