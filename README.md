# 🌍 Location Tracker - Ready to Deploy

## 📁 Deployment Files

- `index.html` - Complete location tracking app (120 lines, minimal code)

## 🚀 Deploy Online (Free)

### Fastest Method - Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `index.html` file
3. Your app is live in 30 seconds!

### Other Options
- **GitHub Pages**: Upload to GitHub repo and enable Pages
- **Vercel**: Drag and drop at vercel.com
- **Firebase**: Upload to Firebase Hosting

## ✅ What It Does

- Gets user's GPS location every 5 minutes
- Sends data to your Supabase API
- Works on mobile and desktop
- Keeps tracking when browser is minimized
- Remembers state across page refreshes

## 🔗 API Configuration

The app sends data to:
```
https://nhfyodexozunbdlz.supabase.co/rest/v1/location
```

Data format:
```json
{
  "lat": "40.7128000",
  "long": "-74.0060000",
  "created_at": "2026-02-17T15:30:00.000Z"
}
```

## 📱 Usage

1. User opens your deployed URL
2. Clicks "Start Tracking"
3. Allows location permission
4. App sends GPS coordinates every 5 minutes automatically

**Note**: User must keep browser tab open for continuous tracking (can be minimized).