ffmpeg -i input.mp4 -g 4 -vcodec libx264 -profile:v main -level:v 4.1 -an -movflags faststart output.mp4


ffmpeg -i input.mp4 -vcodec libx264 -profile:v baseline -level:v 3.1 -movflags +faststart -pix_fmt yuv420p -an output.mp4
