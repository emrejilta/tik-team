import cv2
import glob
for i in range(0, 10):
    path = glob.glob(f"C:\\Users\\Acer\\Desktop\\spectrograms\\{i}\\*.png")

    for photo in path:

        img = cv2.imread(photo)

        img_gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
        img_resize = cv2.resize(img_gray, (600, 600))
        img_normal = cv2.normalize(img_resize, None, alpha=0, beta=200, norm_type=cv2.NORM_MINMAX)
        cv2.destroyAllWindows()
