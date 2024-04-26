/* Styles for the video container */
#video-container {
  max-width: 800px;
  margin: 20px auto;
  background-color: #f4f4f4;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Styles for the video element */
video {
  width: 100%;
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
}

/* Styles for the controls bar */
.controls {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: rgba(0, 0, 0, 0.7);
  padding: 10px;
}

/* Styles for the control buttons */
.controls button {
  background-color: transparent;
  border: none;
  color: #fff;
  cursor: pointer;
  font-size: 20px;
}

/* Style for the download button */
.download-btn button {
  background-color: #4CAF50;
  padding: 8px 16px;
  border-radius: 5px;
  text-transform: uppercase;
  font-weight: bold;
}

/* Styles for the volume button */
#volumeBtn {
  position: relative;
}

/* Style for the volume icon */
#volumeBtn::after {
  content: '\u{1F50A}'; /* Unicode for speaker icon */
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

/* Style for the thumbnail image */
#thumbnail {
  width: 100%;
  display: block;
  border-bottom-left-radius: 8px;
  border-bottom-right-radius: 8px;
}
