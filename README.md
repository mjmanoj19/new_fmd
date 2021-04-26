Face Mask Detection-Project
 
to run:
on an image:python infer.py --img-path \img\path
on a video: python infer.py --img-mode 0 --video-path \video\path
on a webcam: python infer.py --img-mode 0 --video-path 0
on a cctv or external camera connected to the computer: python tensorflow_infer.py --img-mode 0 --video-path <1,2,3(which ever might apply)>

for demo:
on an image:python infer.py --img-path test\demo2.jpg
on a video: python infer.py --img-mode 0 test\wed.mp4
on a webcam: python infer.py --img-mode 0 --video-path 0

you can find the file to download on https://github.com/shivanandham/fmdm/releases
extract the test.zip inside the fmd fot demo to work