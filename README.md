The google collab (ipynb) is the training datasets using 10 University Logo for Datasets:
1. President University
2. California University
3. University of Washington
4. University of Oxford
5. Universitas Pelita Harapan
6. Monika University
7. Harvard University
8. Columbia University
9. Chicago University
10. Cambridge University

For star to detect, run this command in ur command prompt or powershall device:
python detect.py --weights runs/train/exp5/weights/best.pt --img-size 640 --conf 0.4 --source data/test/PU.jpg
python live.py --weights runs/train/exp5/weights/best.pt --conf 0.4 --source 0


