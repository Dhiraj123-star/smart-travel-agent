# 🛫 Travel Planner - Coordinator Agent

Welcome to the **Travel Planner Coordinator**! This system is designed to **gather your travel preferences** and **coordinate with specialized sub-agents** to create a perfect travel plan for you. 🌍✨

## 📋 What It Does

- **Gathers Travel Preferences:**  
  Extracts important details from the user's natural language input, including:
  - Origin (Departure Location)
  - Destination
  - Start Date (format: YYYY-MM-DD)
  - End Date (format: YYYY-MM-DD)
  - Budget Amount
  - Budget Currency (defaults to USD if not specified)

- **Handles Flexible Dates:**  
  Understands phrases like "Next week," "Next month," or "Next year" and converts them into specific dates based on today's date.

- **Fills Missing Information:**  
  - Asks the user to confirm or provide any missing information.
  - Defaults start date to today if not provided.
  - Calculates end date based on the number of days if no end date is given.

- **Confirms Travel Details:**  
  Before proceeding, confirms extracted information with the user (origin, destination, start date, end date, and budget).

- **Coordinates Sub-Agents:**  
  Sends the finalized travel details to:
  - 🛩️ `flight_agent` for flight suggestions
  - 🏨 `hotel_agent` for hotel options

- **Presents Final Results:**  
  Compiles everything into a complete travel plan including:
  - Trip summary (origin, destination, start date, end date, and budget)
  - Flight suggestions ✈️
  - Hotel suggestions 🏨
  - Total estimated cost 💵
  - A suggested day plan with activities and places to visit 📅🏖️

## 💬 Interaction Style

- Friendly, clear, and concise communication
- Asks for missing or unclear details
- Ensures combined cost of flights and hotels stays within the user's maximum budget

## 🔥 Highlights

- Intelligent date conversion and defaults
- Smart handling of missing inputs
- Smooth coordination with flight and hotel agents
- Final result includes a detailed trip summary and daily plan

