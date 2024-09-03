ffmpeg -i input.mp4 -g 4 -vcodec libx264 -profile:v main -level:v 4.1 -an -movflags faststart output.mp4

