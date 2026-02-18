
# Ramadan 2026 Timetable - Yangzhou

A beautiful, interactive web application displaying prayer times and fasting schedule for Ramadan 2026 in Yangzhou, China.

## Features

- **Live Clock Display** - Real-time current local time with live indicator
- **Countdown Timer** - Dynamic countdown to Iftar, Sehri, or next prayer time
- **Today's Highlight** - Quick access to today's Sehri and Iftar times
- **Complete Timetable** - 30-day schedule with filtering options
- **Progress Tracking** - Visual progress bar for Ramadan completion
- **Responsive Design** - Mobile-friendly interface with glassmorphism effects
- **Animated Starfield** - Dynamic background with twinkling stars
- **Duration Calculator** - Shows daily fasting hours

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- Arabic Typography (Noto Naskh Arabic font)

## File Structure

```
├── index.html          # Main application file
├── README.md          # Documentation
```

## Prayer Times Data

- **Location:** Yangzhou, China
- **Period:** February 19 - March 20, 2026
- **Days:** 30
- **Times Included:**
    - Sehri/Imsak (sunrise)
    - Fajr (dawn)
    - Iftar (sunset/Maghrib)

## Usage

1. Open `index.html` in a modern web browser
2. View current time and countdown to next prayer
3. Check today's times in the highlighted section
4. Browse complete 30-day schedule
5. Filter by Past, All, or Upcoming days

## Features Breakdown

### Navigation
- Logo with moon icon
- Location display (Yangzhou, China)
- Current date and time

### Hero Section
- Live clock with seconds
- Moon animation
- Arabic "Ramadan Mubarak" greeting
- Live countdown (Days, Hours, Minutes, Seconds)
- Quick status indicators

### Today's Times
- Sehri/Imsak time with sunset icon
- Iftar time with sun icon
- Fajr begins time
- Total fasting duration

### Complete Timetable
- Day number
- Date
- Sehri, Fajr, Iftar times
- Duration calculation
- Status badges (Today/Completed/Upcoming)
- Filter button controls

### Progress Section
- Percentage bar showing Ramadan completion
- Visual progress indication

## Customization

### Update Times
Edit the `ramadanData` array in the script to adjust prayer times for different locations or years.

### Styling
- Gold color theme: `#d4af37`
- Dark background: `#0f172a`
- Customize via Tailwind config in `<style>` tag

### Location
Change "Yangzhou, China" references to your desired location throughout the HTML.

## Browser Support

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- Times are calculated for Yangzhou, China (2026)
- Actual times may vary based on local moon sighting
- All times displayed in 12-hour format with AM/PM
