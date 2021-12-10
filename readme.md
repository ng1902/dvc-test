# Lets try a thing

<!DOCTYPE html>
<html>
<head>
    <title>DVC Plot</title>
    <script src="https://cdn.jsdelivr.net/npm/vega@5.10.0"></script>
    <script src="https://cdn.jsdelivr.net/npm/vega-lite@4.8.1"></script>
    <script src="https://cdn.jsdelivr.net/npm/vega-embed@6.5.1"></script>
</head>
<body>
    <div id = "plot0"></div>
<script type = "text/javascript">
    var spec = {
    "$schema": "https://vega.github.io/schema/vega-lite/v4.json",
    "data": {
        "values": [
    {
        "precision": 0.021473008227975116,
        "recall": 1.0,
        "rev": "workspace",
        "threshold": 0.0
    },
    {
        "precision": 0.07219662058371736,
        "recall": 0.8785046728971962,
        "rev": "workspace",
        "threshold": 0.02
    },
    {
        "precision": 0.16322701688555347,
        "recall": 0.8130841121495327,
        "rev": "workspace",
        "threshold": 0.04
    },
    {
        "precision": 0.25477707006369427,
        "recall": 0.7476635514018691,
        "rev": "workspace",
        "threshold": 0.06
    },
    {
        "precision": 0.3391304347826087,
        "recall": 0.7289719626168224,
        "rev": "workspace",
        "threshold": 0.08
    },
    {
        "precision": 0.3989071038251366,
        "recall": 0.6822429906542056,
        "rev": "workspace",
        "threshold": 0.1
    },
    {
        "precision": 0.4268292682926829,
        "recall": 0.6542056074766355,
        "rev": "workspace",
        "threshold": 0.12
    },
    {
        "precision": 0.4520547945205479,
        "recall": 0.616822429906542,
        "rev": "workspace",
        "threshold": 0.14
    },
    {
        "precision": 0.4925373134328358,
        "recall": 0.616822429906542,
        "rev": "workspace",
        "threshold": 0.16
    },
    {
        "precision": 0.5333333333333333,
        "recall": 0.5981308411214953,
        "rev": "workspace",
        "threshold": 0.18
    },
    {
        "precision": 0.5727272727272728,
        "recall": 0.5887850467289719,
        "rev": "workspace",
        "threshold": 0.2
    },
    {
        "precision": 0.6039603960396039,
        "recall": 0.5700934579439252,
        "rev": "workspace",
        "threshold": 0.22
    },
    {
        "precision": 0.6263736263736264,
        "recall": 0.5327102803738317,
        "rev": "workspace",
        "threshold": 0.24
    },
    {
        "precision": 0.6506024096385542,
        "recall": 0.5046728971962616,
        "rev": "workspace",
        "threshold": 0.26
    },
    {
        "precision": 0.6666666666666666,
        "recall": 0.4672897196261682,
        "rev": "workspace",
        "threshold": 0.28
    },
    {
        "precision": 0.6428571428571429,
        "recall": 0.4205607476635514,
        "rev": "workspace",
        "threshold": 0.3
    },
    {
        "precision": 0.676923076923077,
        "recall": 0.411214953271028,
        "rev": "workspace",
        "threshold": 0.32
    },
    {
        "precision": 0.6885245901639344,
        "recall": 0.3925233644859813,
        "rev": "workspace",
        "threshold": 0.34
    },
    {
        "precision": 0.6909090909090909,
        "recall": 0.35514018691588783,
        "rev": "workspace",
        "threshold": 0.36
    },
    {
        "precision": 0.7058823529411765,
        "recall": 0.3364485981308411,
        "rev": "workspace",
        "threshold": 0.38
    },
    {
        "precision": 0.7368421052631579,
        "recall": 0.2616822429906542,
        "rev": "workspace",
        "threshold": 0.4
    },
    {
        "precision": 0.7931034482758621,
        "recall": 0.21495327102803738,
        "rev": "workspace",
        "threshold": 0.42
    },
    {
        "precision": 0.8,
        "recall": 0.18691588785046728,
        "rev": "workspace",
        "threshold": 0.44
    },
    {
        "precision": 0.8235294117647058,
        "recall": 0.1308411214953271,
        "rev": "workspace",
        "threshold": 0.46
    },
    {
        "precision": 1.0,
        "recall": 0.08411214953271028,
        "rev": "workspace",
        "threshold": 0.48
    },
    {
        "precision": 1.0,
        "recall": 0.06542056074766354,
        "rev": "workspace",
        "threshold": 0.5
    },
    {
        "precision": 1.0,
        "recall": 0.056074766355140186,
        "rev": "workspace",
        "threshold": 0.52
    },
    {
        "precision": 1.0,
        "recall": 0.04672897196261682,
        "rev": "workspace",
        "threshold": 0.56
    },
    {
        "precision": 1.0,
        "recall": 0.018691588785046728,
        "rev": "workspace",
        "threshold": 0.58
    },
    {
        "precision": 1.0,
        "recall": 0.009345794392523364,
        "rev": "workspace",
        "threshold": 0.6
    }
]
    },
    "title": "",
    "width": 300,
    "height": 300,
    "mark": {
        "type": "line"
    },
    "encoding": {
        "x": {
            "field": "recall",
            "type": "quantitative",
            "title": "recall"
        },
        "y": {
            "field": "precision",
            "type": "quantitative",
            "title": "precision",
            "scale": {
                "zero": false
            }
        },
        "color": {
            "field": "rev",
            "type": "nominal"
        }
    }
}
;
    vegaEmbed('#plot0', spec);
</script>
<div id = "plot1"></div>
<script type = "text/javascript">
    var spec = {
    "$schema": "https://vega.github.io/schema/vega-lite/v4.json",
    "data": {
        "values": [
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 1.6,
        "tpr": 0.0
    },
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 0.6,
        "tpr": 0.009345794392523364
    },
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 0.58,
        "tpr": 0.018691588785046728
    },
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 0.56,
        "tpr": 0.04672897196261682
    },
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 0.5,
        "tpr": 0.06542056074766354
    },
    {
        "fpr": 0.0,
        "rev": "workspace",
        "threshold": 0.48,
        "tpr": 0.08411214953271028
    },
    {
        "fpr": 0.0006152584085315833,
        "rev": "workspace",
        "threshold": 0.46,
        "tpr": 0.1308411214953271
    },
    {
        "fpr": 0.001025430680885972,
        "rev": "workspace",
        "threshold": 0.44,
        "tpr": 0.18691588785046728
    },
    {
        "fpr": 0.0012305168170631665,
        "rev": "workspace",
        "threshold": 0.42,
        "tpr": 0.21495327102803738
    },
    {
        "fpr": 0.002050861361771944,
        "rev": "workspace",
        "threshold": 0.4,
        "tpr": 0.2616822429906542
    },
    {
        "fpr": 0.0030762920426579163,
        "rev": "workspace",
        "threshold": 0.38,
        "tpr": 0.3364485981308411
    },
    {
        "fpr": 0.003486464315012305,
        "rev": "workspace",
        "threshold": 0.36,
        "tpr": 0.35514018691588783
    },
    {
        "fpr": 0.003896636587366694,
        "rev": "workspace",
        "threshold": 0.34,
        "tpr": 0.3925233644859813
    },
    {
        "fpr": 0.004306808859721083,
        "rev": "workspace",
        "threshold": 0.32,
        "tpr": 0.411214953271028
    },
    {
        "fpr": 0.005127153404429861,
        "rev": "workspace",
        "threshold": 0.3,
        "tpr": 0.4205607476635514
    },
    {
        "fpr": 0.005127153404429861,
        "rev": "workspace",
        "threshold": 0.28,
        "tpr": 0.4672897196261682
    },
    {
        "fpr": 0.005947497949138638,
        "rev": "workspace",
        "threshold": 0.26,
        "tpr": 0.5046728971962616
    },
    {
        "fpr": 0.00697292863002461,
        "rev": "workspace",
        "threshold": 0.24,
        "tpr": 0.5327102803738317
    },
    {
        "fpr": 0.008203445447087777,
        "rev": "workspace",
        "threshold": 0.22,
        "tpr": 0.5700934579439252
    },
    {
        "fpr": 0.009639048400328138,
        "rev": "workspace",
        "threshold": 0.2,
        "tpr": 0.5887850467289719
    },
    {
        "fpr": 0.011484823625922888,
        "rev": "workspace",
        "threshold": 0.18,
        "tpr": 0.5981308411214953
    },
    {
        "fpr": 0.01394585726004922,
        "rev": "workspace",
        "threshold": 0.16,
        "tpr": 0.616822429906542
    },
    {
        "fpr": 0.016406890894175553,
        "rev": "workspace",
        "threshold": 0.14,
        "tpr": 0.616822429906542
    },
    {
        "fpr": 0.019278096800656275,
        "rev": "workspace",
        "threshold": 0.12,
        "tpr": 0.6542056074766355
    },
    {
        "fpr": 0.022559474979491387,
        "rev": "workspace",
        "threshold": 0.1,
        "tpr": 0.6822429906542056
    },
    {
        "fpr": 0.031173092698933553,
        "rev": "workspace",
        "threshold": 0.08,
        "tpr": 0.7289719626168224
    },
    {
        "fpr": 0.04799015586546349,
        "rev": "workspace",
        "threshold": 0.06,
        "tpr": 0.7476635514018691
    },
    {
        "fpr": 0.09146841673502872,
        "rev": "workspace",
        "threshold": 0.04,
        "tpr": 0.8130841121495327
    },
    {
        "fpr": 0.24774405250205087,
        "rev": "workspace",
        "threshold": 0.02,
        "tpr": 0.8785046728971962
    },
    {
        "fpr": 1.0,
        "rev": "workspace",
        "threshold": 0.0,
        "tpr": 1.0
    }
]
    },
    "title": "",
    "width": 300,
    "height": 300,
    "mark": {
        "type": "line"
    },
    "encoding": {
        "x": {
            "field": "fpr",
            "type": "quantitative",
            "title": "fpr"
        },
        "y": {
            "field": "tpr",
            "type": "quantitative",
            "title": "tpr",
            "scale": {
                "zero": false
            }
        },
        "color": {
            "field": "rev",
            "type": "nominal"
        }
    }
}
;
    vegaEmbed('#plot1', spec);
</script>
</body>
</html>