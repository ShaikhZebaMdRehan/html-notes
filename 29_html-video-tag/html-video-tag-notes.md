<!-- +++++++++++++++ HTML Video +++++++++++++++ -->
=> The <video> tag is a block-level element for embedding video files.
=> Supported formats: MP4, WebM, Ogg.
=> <source> in <video> needs type attribute to specify file format.
src → video file path
type → format (e.g., video/mp4, video/ogg)
Example: <video controls>
	        <source src="01.mp4" type="video/mp4">
        </video>

<!-- +++++++++++++++ Video Attributes +++++++++++++++ -->
1. src → video file path
2. height → set video height
3. width → set video width
4. controls → display video controls
5. loop → play video repeatedly
6. autoplay → play video automatically
7. muted → mute video
8. preload → load video when page loads
preload values:
auto → load entire video
metadata → load only metadata
none → do not load video