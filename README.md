# Arcade Hub - 19 Classic Arcade Games!

🎮 **Play now:** [https://arcade-engine.com](https://arcade-engine.com)

A collection of 19 mini arcade games built with HTML5 Canvas and JavaScript, fully optimized for touchscreen devices with a beautiful purple neon home menu interface.

## 🎯 Features

- **Home Menu**: Start with an attractive purple neon game selection screen
- **19 Classic Games**: Basketball, Football, Racing, Flappy Bird, Snake, Pong, Breakout, Space Invaders, Asteroids, Frogger, Dodge, Tetris, Pac-Man, Galaga, Centipede, Missile Command, Qix, Arkanoid, and Bubble Bobble
- **Touch Controls**: Virtual joystick and action button for mobile play
- **Keyboard Support**: WASD/Arrow keys + Space/Enter
- **Responsive Design**: Works on desktop and mobile devices
- **Voice Announcements**: Audio feedback for game events

## 🎮 Games Included

### 🏀 Basketball | 🏈 Football | 🏁 Racing | 🐦 Flappy Bird
### 🐍 Snake | 🏓 Pong | 🧱 Breakout | 🚀 Space Invaders
### ☄️ Asteroids | 🐸 Frogger | ⚡ Dodge | 🧩 Tetris
### 👻 Pac-Man | 🚀 Galaga | 🐛 Centipede | 🚀 Missile Command
### 🌀 Qix | 🎯 Arkanoid | 🫧 Bubble Bobble

## 📱 Controls

- **Touch**: Virtual joystick (bottom-left) + Action button (bottom-right)
- **Keyboard**: WASD/Arrow keys + Space/Enter
- **Mobile**: Fully responsive with touch-optimized controls

## 🚀 Publishing Guide

### Option 1: GitHub Pages (Free & Recommended)
1. Create a GitHub account at [github.com](https://github.com)
2. Create a new repository named `arcade-hub`
3. Upload all files from this folder to your repository
4. Go to **Settings** → **Pages** → **Source**: "main" → **Save**
5. Your site will be live at: `https://arcade-engine.com`

### Option 2: Netlify (Free & Instant)
1. Go to [netlify.com](https://netlify.com)
2. **Drag and drop** the entire `arcade-hub` folder onto the upload area
3. Your site gets a random URL instantly! (e.g., `https://amazing-site-123.netlify.app`)

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Click **"Import Project"**
3. Upload your files or connect your GitHub
4. Deploy instantly with a custom domain option

### Option 4: Other Free Hosts
- **GitLab Pages**: Similar to GitHub Pages
- **Surge.sh**: `npm install -g surge` then `surge`
- **Firebase Hosting**: `firebase deploy`
- **Render.com**: Free static site hosting

## � Deployment Files

Your project includes helper files for easy deployment:

- **`deploy.bat`** - Interactive deployment assistant with step-by-step instructions
- **`test-local.bat`** - Start a local test server at http://localhost:8000
- **`package.json`** - NPM scripts for advanced deployment options
- **`.nojekyll`** - Required for GitHub Pages to serve files correctly

### Quick Test
Double-click `test-local.bat` to test your site locally before publishing!

## �🛠️ Tech Stack

- **HTML5 Canvas** for smooth game rendering
- **Vanilla JavaScript** for game logic and physics
- **CSS3** with responsive design and neon effects
- **Touch API** for mobile controls
- **Speech Synthesis** for voice announcements

## 📄 License

Feel free to use, modify, and share! This is a fun project for learning game development.

---

**Built with ❤️ for retro gaming enthusiasts!** 🎮✨

### 🏀 Basketball
- Use joystick to move player
- Tap ACTION button to shoot
- Score by getting the ball through the hoop

### 🏈 Football
- Use joystick to move player
- Tap ACTION button to throw the ball
- Score touchdowns by throwing to the end zone

### 🏁 Racing
- Use joystick left/right to steer
- Avoid red obstacles (other cars)
- Complete laps automatically

### 🐦 Flappy
- Use joystick up/down for minor adjustments
- Tap ACTION button to flap/jump
- Navigate through green pipe gaps

### 🐍 Snake
- Use joystick to change direction (up/down/left/right)
- Eat red food squares to grow
- Avoid walls and yourself

### 🏓 Pong
- Use joystick up/down to move paddle
- Hit the ball past your opponent
- First to score wins

### 🧱 Breakout
- Use joystick left/right to move paddle
- Break all red bricks with the ball
- Don't let the ball fall off screen

### 🚀 Space
- Use joystick left/right to move ship
- Tap ACTION button to shoot
- Destroy red enemy invaders

### ☄️ Asteroids
- Use joystick left/right to rotate ship
- Tap ACTION button to shoot
- Destroy floating asteroids

### 🐸 Frogger
- Use joystick to move frog
- Cross roads and reach the goal
- Avoid moving cars

### ⚡ Dodge
- Use joystick left/right to move
- Survive falling obstacles
- Score increases over time

### 🧩 Tetris
- Use joystick left/right to move pieces
- Tap ACTION button to rotate
- Clear complete lines

### 👻 Pac-Man
- Use joystick to move Pac-Man
- Eat all white dots
- Avoid colorful ghosts

### 🚀 Galaga
- Use joystick left/right to move ship
- Tap ACTION button to shoot
- Destroy alien formations

### 🐛 Centipede
- Use joystick left/right to move
- Tap ACTION button to shoot
- Stop the centipede segments

### 🚀 Missile Command
- Use joystick to aim launcher
- Tap ACTION button to fire missiles
- Protect cities from attacks

### 🌀 Qix
- Use joystick to move player
- Tap ACTION button to draw trails
- Claim 75% of the area

### 🎯 Arkanoid
- Use joystick left/right to move paddle
- Bounce ball to break blocks
- Clear all colored blocks

### 🫧 Bubble Bobble
- Use joystick left/right to move
- Tap ACTION button to shoot bubbles
- Match colors to clear bubbles

## Touchscreen Controls

### Virtual Joystick
- **Location**: Bottom-left corner of screen
- **How to use**: Touch and drag the white circle within the gray base to control movement
- **Games**: Used for movement in Basketball, Football, Racing, Flappy, Snake, Pong, Breakout, and Space

### Action Button
- **Location**: Bottom-right corner of screen
- **How to use**: Tap to perform game-specific actions
- **Visual feedback**: Button darkens and shrinks when pressed

## Mobile Features

- **Responsive Design**: Canvas and controls automatically resize for different screen sizes
- **Touch-Optimized**: Prevents scrolling, zooming, and other default touch behaviors
- **Orientation Support**: Handles screen rotation and orientation changes
- **Multi-Touch**: Properly handles multiple simultaneous touches
- **Visual Feedback**: Buttons and joystick provide immediate visual response

## Desktop Controls (Still Available)

- **WASD** or **Arrow Keys** for movement
- **Space** or **Enter** for action button

## Technical Improvements

1. **Enhanced Touch Handling** - Proper multi-touch support with touch identification
2. **Responsive Canvas** - Dynamic sizing based on device screen
3. **Touch Event Prevention** - Blocks interfering browser behaviors
4. **Mobile Viewport** - Optimized meta tags for mobile browsers
5. **CSS Touch Properties** - Prevents text selection and improves touch response
6. **Orientation Changes** - Automatic canvas resizing on device rotation

## Browser Compatibility

Works on all modern browsers with touch support:
- iOS Safari
- Chrome Mobile
- Firefox Mobile
- Samsung Internet
- And desktop browsers with touch simulation

## How to Run

Simply open `index.html` in any modern web browser. The game automatically detects touch capabilities and provides appropriate controls.

## Touchscreen Controls

### Virtual Joystick
- **Location**: Bottom-left corner of screen
- **How to use**: Touch and drag the white circle within the gray base to control movement
- **Games**: Used for movement in Basketball, Football, Racing, and Flappy Bird

### Action Button
- **Location**: Bottom-right corner of screen
- **How to use**: Tap to perform game-specific actions
- **Visual feedback**: Button darkens and shrinks when pressed

## Games

### 🏀 Basketball
- Use joystick to move player
- Tap ACTION button to shoot
- Score by getting the ball through the hoop

### 🏈 Football
- Use joystick to move player
- Tap ACTION button to throw the ball
- Score touchdowns by throwing to the end zone

### 🏁 Racing
- Use joystick left/right to steer
- Avoid red obstacles (other cars)
- Complete laps automatically

### 🐦 Flappy
- Use joystick up/down for minor adjustments
- Tap ACTION button to flap/jump
- Navigate through green pipe gaps

## Mobile Features

- **Responsive Design**: Canvas and controls automatically resize for different screen sizes
- **Touch-Optimized**: Prevents scrolling, zooming, and other default touch behaviors
- **Orientation Support**: Handles device rotation and orientation changes
- **Multi-Touch**: Properly handles multiple simultaneous touches
- **Visual Feedback**: Buttons and joystick provide immediate visual response

## Desktop Controls (Still Available)

- **WASD** or **Arrow Keys** for movement
- **Space** or **Enter** for action button

## Technical Improvements

1. **Enhanced Touch Handling** - Proper multi-touch support with touch identification
2. **Responsive Canvas** - Dynamic sizing based on device screen
3. **Touch Event Prevention** - Blocks interfering browser behaviors
4. **Mobile Viewport** - Optimized meta tags for mobile devices
5. **CSS Touch Properties** - Prevents text selection and improves touch response
6. **Orientation Changes** - Automatic canvas resizing on device rotation

## Browser Compatibility

Works on all modern browsers with touch support:
- iOS Safari
- Chrome Mobile
- Firefox Mobile
- Samsung Internet
- And desktop browsers with touch simulation

## How to Run

Simply open `index.html` in any modern web browser. The game automatically detects touch capabilities and provides appropriate controls.</content>
<parameter name="filePath">c:\Users\gmadd\Desktop\arcade-hub\README.md