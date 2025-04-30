# gif-cutting

Python con imageio o Pillow + moviepy:
```
from moviepy.editor import VideoFileClip

clip = VideoFileClip("original.gif")
final_part = clip.subclip(3, clip.duration)  # por ejemplo, últimos segundos desde el 3 hasta el final
final_part.write_gif("final.gif")
```
