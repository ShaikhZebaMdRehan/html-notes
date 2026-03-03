<!-- +++++++++++++++ HTML Audio +++++++++++++++ -->
=> The <audio> tag is an inline element for embedding sound files.
=> It is useful for adding audio like songs or interviews.
=> Supported formats: MP3, WAV, OGG.
=> <source> in <audio> needs type attribute to specify file format.
src → audio file path
type → format (e.g., audio/mp3, audio/ogg)
Example: <audio controls>
	        <source src="01.mp3" type="audio/mp3">
        </audio>

<!-- +++++++++++++++ Audio Attributes +++++++++++++++ -->
1. src → audio file path
2. height → set audio height
3. width → set audio width  
4. controls → display audio controls
5. loop → play audio repeatedly
6. autoplay → play audio automatically
7. muted → mute audio
8. preload → load audio when page loads
preload values:
auto → load entire audio
metadata → load only metadata
none → do not load audio