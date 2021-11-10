# Template Tracking

In this work we do object tracking using classical computer vision methods like Block-based matching (sliding-window method) and Lucas-Kanade Algorithm. The problem statement can be found [here](./Assignment_2.pdf) and detailed discussion can be found [here](./Report.pdf).

## Running Mode

Predict the bounding boxes using block-based matching (method 1), LK algorithm (method 2), or Pyramid-based LK Algorithm (method 3)

```bash
python main.py  -i=<path to input frames> --method=<1/2/3>
```

Evaluate the predicted bounding boxes against ground truth

```bash
python eval.py  --p=<path to predictions.txt> --g=<path to groundtruth.txt>
```

**Live tracker**

```
python livetracker.py --method=<1/2/3>
```

## Authors

- [Shubham Mittal](https://www.linkedin.com/in/shubham-mittal-6a8644165/)
- [Aditi Khandelwal](https://www.linkedin.com/in/aditi-khandelwal-991b1b19b/)

Course assignment in Computer Vision course ([course webpage](https://www.cse.iitd.ac.in/~chetan/teaching/col780-2020.html)) taken by [Prof. Chetan Arora](https://www.cse.iitd.ac.in/~chetan)
