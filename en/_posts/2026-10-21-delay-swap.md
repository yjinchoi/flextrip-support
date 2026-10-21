---
lang: en
title: Add transport and times, and swap places when you run late
description: Add transport and travel times to a simple day plan, keep a few backup places ready, and when you fall behind, replace the place you can no longer reach with one of them.
date: 2026-10-21 11:00:00 +0900
permalink: /en/blog/delay-swap/
redirect_from:
  - /en/blog/day-plan/
  - /en/blog/change-plans/
alt: /blog/delay-swap/
series: guide
image: /assets/img/blog/p2-late.png
---

Once you add transport and travel times to a route, Flex Trip Planner works out arrival and departure times for every visit and builds a timetable for the day. With a timetable, you can see right away what to drop when you fall behind on the day.

Our example is a day in Seoul. Start at Seoul Station, visit Gyeongbokgung Palace, Bukchon Hanok Village and N Seoul Tower, then have an early dinner at a restaurant in Gwangjang Market booked for 5:30 PM. Changdeokgung Palace and Cheonggyecheon Stream, both nearby, are kept as backups.

The app's screens are in Korean. Below, button names are given in Korean with an English translation.

## 1. Add transport and travel time to a leg

Tap the row between two visits (a leg) to open the **구간 이동수단** (Leg transport) editor. Tap **옵션 추가** (Add option), pick a mode (subway, bus, walk, taxi and more), enter **합계 소요 시간(분)** (Total travel time, minutes) and save. You can leave the fare and line number blank.

{% include shot.html src="p2-leg-option" alt="Add transport option form (Seoul Station → Gyeongbokgung): total travel time 20 minutes, select on this leg after saving turned on" caption="Adding a 20-minute subway ride to a leg" %}

You can keep several options on one leg (say, subway 20 min and taxi 15 min) and pick one. Options between the same two places can be reused on other days.

## 2. Set how long you stay at each visit

Tap a visit to open the editor and set **체류 시간** (Time spent). Enter 2 hours for Gyeongbokgung, 1 hour for Bukchon and so on, and the day's timetable is calculated for you.

{% include shot.html src="p2-day-card" alt="Day 1 card: Seoul Station 09:00, subway 20 min, Gyeongbokgung 09:20–11:20, walk 15 min, Bukchon Hanok Village 11:35–13:05" caption="A day plan with calculated times" %}

If a time is fixed, enter it as **고정 도착 시각** (Fixed arrival time) in the visit editor. Here the Gwangjang Market booking at 17:30 is fixed.

## 3. Keep backup places ready

Places you might visit if you have time go into your saved places on the **장소** (Places) tab. Saved places can be picked straight away when you add a visit.

{% include shot.html src="p2-candidates" alt="Saved places list on the Places tab: Changdeokgung, Cheonggyecheon, Gwangjang Market, Gyeongbokgung and more" caption="Backup places kept in your saved places" %}

## 4. A warning appears when you fall behind

Say you spend longer than planned at Gyeongbokgung. Change its time spent to 3 hours, and every later time moves back, so you'd miss the fixed 17:30 booking at Gwangjang Market. The visit card gets a **지연 n분** (n min late) badge, and the warning also shows in the **경고** (Warnings) list at the top of the trip.

{% include shot.html src="p2-late" alt="N Seoul Tower 14:30–17:30, then Gwangjang Market arriving 18:00 with a fixed 17:30, a 30 min late badge, and 1 warning at the top" caption="A late badge when you'll miss a booked time" %}

Tap a warning to jump straight to that visit's editor.

## 5. Remove the place you can't reach and add a backup

Now take out the place you no longer have time for. In the menu of N Seoul Tower, which is far from the rest, tap **방문 삭제** (Delete visit). If you remove the wrong one, tap **실행 취소** (Undo) in the message that appears.

{% include shot.html src="p2-remove" alt="Menu for the N Seoul Tower visit: edit visit, find tickets and tours, move up, move down, set position, delete visit" caption="Deleting a visit from its menu" %}

Then fill the gap with a nearby backup. Tap **+** (Add a place here) on the leg row between Bukchon Hanok Village and Gwangjang Market. The place picker opens, and **추천 방문 장소** (Suggested places) lists your saved places by distance from the place just before the gap (Bukchon). Pick Changdeokgung, which you saved earlier.

{% include shot.html src="p2-picker-nearby" alt="Suggested places in the add-visit picker, by distance from Bukchon Hanok Village: Changdeokgung 620 m, Cheonggyecheon 1.6 km, N Seoul Tower 3.5 km" caption="Picking a backup from suggested places" %}

Add Changdeokgung, set its time spent to 2 hours 30 minutes, and the timetable is recalculated. You now reach Gwangjang Market before the booked time, so the late warning disappears and the spare time shows as **대기 30분** (30 min wait). If you already added transport between your backup places, those times are used too.

{% include shot.html src="p2-resolved" alt="Bukchon Hanok Village, walk 10 min, Changdeokgung 14:15–16:45, taxi 15 min, Gwangjang Market 17:30–18:30 fixed at 17:30, 30 min wait" caption="The day after swapping in a backup" %}

## Summary

- Add **transport and travel times** to legs and **time spent** to visits, and the day's timetable is calculated for you.
- Set times you must keep as **고정 도착 시각** (Fixed arrival time), and a **지연 n분** (n min late) warning tells you when you'll miss them.
- Keep backups in your saved places. When you fall behind, delete a visit and use **+** on the leg row to add a nearby backup from **추천 방문 장소** (Suggested places).
