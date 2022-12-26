
# sentimentID

Calculate And Get Sentiment Score For Indonesian Language


## Installing

Using npm:

    npm i @rahadiana/sentimenid


**USAGE**

    const {SentimentId} = require("@rahadiana/sentimenid");
    console.log(SentimentId('aku benci kamu , tetapi aku sayang kamu'))
    

SUCCESS RESPONE

    {"score":1,"sentiment":"positive","comparative":0.14285714285714285,"calculation":[{"sayang":3},{"benci":-2}],"tokens":["aku","benci","kamu","tetapi","aku","sayang","kamu"],"words":["sayang","benci"],"positive":["sayang"],"negative":["benci"]}
