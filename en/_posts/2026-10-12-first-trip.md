---
lang: en
title: Create Your First Trip — Start with Dates and Departure and Arrival Places
description: Create a new trip in FlexTrip and take a look at how the itinerary screen is laid out.
date: 2026-10-12 09:00:00 +0900
permalink: /en/blog/first-trip/
alt: /blog/first-trip/
series: guide
image: /assets/img/blog/01-trip-form.png
---

Planning a trip starts with "when, where you leave from, and where you end up." Set just those three things and FlexTrip automatically creates a slot for each day of your itinerary. In this post, we'll create a first trip using a May 2027 trip to Paris as an example.

## 1. Tap "Create your first trip" on the Trips tab

When you open the app for the first time, the **Trips** (여행) tab shows "No trips yet." (아직 여행이 없습니다.). Tap **Create your first trip** (첫 여행 만들기). If you have a KML file exported from Google Maps, you can also start with **Create a trip from a file** (파일로 여행 만들기) to bring in all your places at once.

{% include shot.html src="01-trip-list-empty" alt="Empty list on the Trips tab with the Create your first trip button" caption="Trips tab — Create your first trip" %}

## 2. Title, travelers, and departure

On the **New trip** (새 여행) screen, fill things in from the top.

- **Title** (제목): A name that's easy to spot in your list (for example, Paris Trip).
- **Travelers** (인원): The number of people going, set with the −/+ buttons. Per-person costs such as admission fees are multiplied by this number to get the total.
- **Departure date and time** (출발일·출발 시각): Tap the date field to open a calendar, and use ‹ › to switch months. The departure time defaults to 09:00, and Day 1 starts at this time.
- **Departure place** (출발 장소): Where your trip begins, such as your home or an airport. Type a name in the place search box and pick one.

Once you pick a departure place, its time zone appears below, such as "Based on Asia/Seoul" (Asia/Seoul 기준). FlexTrip remembers the local time zone of each place, so even on trips that cross borders, times are shown in local time.

<div class="shots">
{% include shot.html src="01-trip-form" alt="Top of the New trip screen: title, travelers, departure date, departure time, departure place" caption="Title, travelers, departure" %}
{% include shot.html src="01-trip-form-bottom" alt="Bottom of the New trip screen: arrival date, arrival time, arrival place, trip currency" caption="Arrival and trip currency" %}
</div>

## 3. Arrival details and trip currency

- **Arrival date** (도착일): The last day of your trip. A slot is created for every day between the departure and arrival dates (Day 1, Day 2, and so on).
- **Expected arrival time** (도착 예정 시각): Optional. Enter it only if you have a set time to get back.
- **Arrival place** (도착 장소): Where your trip ends. For a round trip, make it the same as the departure place; if the trip ends at a local airport, as in this example, pick that airport.
- **Trip currency and exchange rate** (여행 통화와 환율): Add the local currency (for example, EUR) and enter an exchange rate, and costs will also be shown in your base currency (KRW).

<p class="tip">You can change dates and places anytime with <strong>Edit info</strong> (정보 수정) on the Info tab. If you shorten the trip, the app first asks what to do with the visits on the days that go away.</p>

## 4. Save, and the itinerary screen opens

After you save, you go straight to the **Trip itinerary** (여행 일정) screen. The map is at the top, and below it is an itinerary sheet you can drag up and down. The sheet has four tabs at the top.

- **Itinerary** (일정): Cards for each day. Tap a card to see that day's route on the map.
- **Costs** (비용): Cost totals by day and by item.
- **Checklist** (체크리스트): Things to pack and things to do.
- **Info** (정보): Lodging and flights, editing trip info, and importing and exporting files.

{% include shot.html src="01-trip-created" alt="New trip itinerary screen with a prompt to add lodging and flights" caption="The itinerary screen right after creating a trip" %}

The Day 1 card has your departure place as the first visit and shows the departure time, such as "Starts 09:00" (09:00 시작). A newly created trip shows a one-time prompt: "Have you booked lodging or flights?" (숙소·항공권을 예약했나요?). If you already have lodging and flights booked, tap **Add them** (등록하기) to put them in your itinerary. We'll cover this in detail in the next post.

## Summary

- All you need to create a trip is a title, departure (date, time, place), and arrival (date, place).
- Every place has a time zone, so trips abroad are planned in local time.
- You can change dates, places, and the number of travelers anytime on the Info tab.
