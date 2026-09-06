Trained with Ultralytics YOLO under [GNU AGPL v3](LICENSE).

## Model
Weights: `/content/runs/classify/train/weights/best.pt`
Trained with:

```bash
yolo classify train model=yolo26n-cls.pt data=/content/dataset epochs=300 patience=100 imgsz=224 fliplr=0.0 scale=0.2 dropout=0.1
```

## License
This model is licensed under the GNU Affero General Public License v3.
The source code of the Ultralytics framework is available [here](https://github.com/ultralytics/ultralytics).
