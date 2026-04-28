body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: white;
  overflow-x: hidden;

  /* Blue lightning sky background */
  background: radial-gradient(circle at top, #1e3c72, #0f2027, #000000);
}

/* Lightning container */
#lightning-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 0;
}

/* Lightning bolt */
.lightning {
  position: absolute;
  width: 3px;
  height: 250px;
  background: #9be7ff;
  opacity: 0;
  box-shadow: 
    0 0 10px #9be7ff,
    0 0 20px #00cfff,
    0 0 40px #00cfff,
    0 0 80px #00cfff;
  transform: skewX(-20deg);
}

/* Header */
header {
  position: relative;
  z-index: 1;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: rgba(0,0,40,0.7);
  padding: 1rem;
}

.menu-btn {
  font-size: 20px;
  background: none;
  border: none;
  color: white;
  cursor: pointer;
}

nav {
  display: none;
  flex-direction: column;
}

nav a {
  color: #9be7ff;
  text-decoration: none;
  margin: 5px 0;
}

.content {
  position: relative;
  z-index: 1;
  text-align: center;
  padding: 2rem;
}

/* Sparkle text */
.sparkle:hover {
  text-shadow: 
    0 0 5px white,
    0 0 10px #00cfff,
    0 0 20px #00cfff,
    0 0 40px #00cfff;
  cursor: pointer;
}

/* Button */
button {
  padding: 10px 20px;
  border: none;
  background: #00cfff;
  color: #003366;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background: #0099cc;
}
