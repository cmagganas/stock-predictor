# stock-predictor
Stock Prophet

### cmd:
```bash
curl --header "Content-Type: application/json" --request POST --data '{"ticker":"MSFT", "days":7}' http://52.11.249.0:8000/predict
```
### output:
```
{"ticker":"MSFT","days":7,"forecast":{"03/10/2023":245.28347058864819,"03/11/2023":245.26532916753953,"03/12/2023":245.24718774643088,"03/13/2023":245.22904632532223,"03/14/2023":245.21090490421358,"03/15/2023":245.19276348310493,"03/16/2023":245.17462206199627}}
```

<img src="img/week-12-MLOps0-screenshot-1.png" alt="drawing" width="400"/>