# family_tree


![Alt text](https://g.gravizo.com/source/custom_mark1?https%3A%2F%2Fgithub.com%2Fbbbalabhaskar%2Ffamily_tree%2Fblob%2Fmain%2FREADME.md)


```
![Alt text](https://g.gravizo.com/source/custom_mark1?https%3A%2F%2Fgithub.com%2Fbbbalabhaskar%2Ffamily_tree%2Fblob%2Fmain%2FREADME.md)
<details> 
<summary></summary>
custom_mark1
  digraph g {
    fontname="Helvetica,Arial,sans-serif"
    node [fontname="Helvetica,Arial,sans-serif"]
    edge [fontname="Helvetica,Arial,sans-serif"]

    graph [
    rankdir = "LR"
    ];

    edge [
    ];

    M1 [shape=record, color=blue, style=bold, label="వీరయ్య"]
    M2 [shape=record, color=blue, style=bold, label="<f0>సుబ్రహ్మమణ్యం | <f1> వెంకమ్మ "]
    M1 -> "M2":f0  [style=bold,color=blue];

    M4 [shape=record, color=blue, style=bold, label="<f0>వీరయ్య | <f1> వెంకమ్మ"]
    "M2":f0 -> "M4":f0 [style=bold,color=blue];

    M6 [shape=record, color=blue, style=bold, label="<f0>సుబ్రహ్మమణ్యం | <f1> నిస్సంతు"]
    "M4":f0 -> "M6":f0 [style=bold,color=blue];
    M8 [shape=record, color=blue, style=bold, label="<f0>పేరయ్య | <f1> నిస్సంతు"]
    "M4":f0 -> "M8":f0 [style=bold,color=blue];
    M10 [shape=record, color=blue, style=bold, label="<f0>మందయ్య | <f1> నిస్సంతు"]
    "M4":f0 -> "M10":f0 [style=bold,color=blue];
    M12 [shape=record, color=blue, style=bold, label="<f0>రామయ్య | <f1> బాపనమ్మ"]
    "M4":f0 -> "M12":f0 [style=bold,color=blue];
    M14 [shape=record, color=blue, style=bold, label="<f0>నాగయ్య | <f1> సూరయ్య\n(నిస్సంతు)"]
    "M4":f0 -> "M14":f0 [style=bold,color=blue];
    M16 [shape=record, color=blue, style=bold, label="<f0>సూరావధాని | <f1> పిచ్చమ్మ"]
    "M4":f0 -> "M16":f0 [style=bold,color=blue];

    M17 [shape=record, color=blue, style=bold, label="<f0>కాంతం|<f1>వేంకటసుబ్బమ్మ"]
    "M12":f0 -> "M17":f0 [style=bold,color=blue];

    M18 [shape=record, color=blue, style=bold, label="<f0>శ్రీరామమూర్తి|<f1>లక్ష్మీనరసమ్మ"]
    "M17":f0 -> "M18":f0 [style=bold,color=blue];

    M19 [shape=record, color=blue, style=bold, label="లక్ష్మీనరసింహముర్తి"]
    "M18":f0 -> "M19" [style=bold,color=blue];

    M20 [shape=record, color=blue, style=bold, label="<f0>కృష్ణసోమయాజి|<f1>అన్నపూర్ణమ్మ"]
    "M16":f0 -> "M20":f0 [style=bold,color=blue];
    M21 [shape=record, color=blue, style=bold, label="శ్రీరామమూర్తి"]
    "M16":f0 -> "M21" [style=bold,color=blue];
    M22 [shape=record, color=blue, style=bold, label="<f0>పట్టాభిరామయ్య|<f1>శాయమ్మ"]
    "M16":f0 -> "M22":f0 [style=bold,color=blue];
    M23 [shape=record, color=blue, style=bold, label="<f0>వెంకటాద్రి|<f1>వెంకాయమ్మ"]
    "M16":f0 -> "M23":f0 [style=bold,color=blue];
    M24 [shape=record, color=blue, style=bold, label="<f0>వీరన్న|<f1>అన్నపూర్ణమ్మ"]
    "M16":f0 -> "M24":f0 [style=bold,color=blue];

    M25 [shape=record, color=blue, style=bold, label="<f0>సుర్యప్రకాశ శర్మ|<f1>సత్యవతి"]
    "M20":f0 -> "M25":f0 [style=bold,color=blue];
    M26 [shape=record, color=blue, style=bold, label="శ్రీ రామ మూర్తి\n(దత్తకః)"]
    "M20":f0 -> "M26" [style=bold,color=blue];
    M27 [shape=record, color=blue, style=bold, label="<f0>సత్యనారాయణ|<f1>______"]
    "M20":f0 -> "M27":f0 [style=bold,color=blue];
    M28 [shape=record, color=blue, style=bold, label="<f0>విద్యానాధశాస్త్రి|<f1>భాస్కరాంబ"]
    "M20":f0 -> "M28":f0 [style=bold,color=blue];
    M29 [shape=record, color=blue, style=bold, label="<f0>బ్రహ్మావధాని|<f1>సువర్చల|<f2>బాలాత్రిపురసుందరి"]
    "M20":f0 -> "M29":f0 [style=bold,color=blue];

    M30 [shape=record, color=blue, style=bold, label="<f0>కృష్ణ సోమయాజి|<f1>సావిత్రి"]
    "M27":f0 -> "M30":f0 [style=bold,color=blue];
    M31 [shape=record, color=blue, style=bold, label="<f0>శ్యామలరావ్|<f1>రాజ్యలక్ష్మి"]
    "M27":f0 -> "M31":f0 [style=bold,color=blue];

    M32 [shape=record, color=blue, style=bold, label="<f0>సత్యనారాయణమూర్తి|<f1>దుర్గ విశాలి"]
    "M30":f0 -> "M32":f0 [style=bold,color=blue];
    M33 [shape=record, color=blue, style=bold, label="నాగసీతారామ్"]
    "M30":f0 -> "M33" [style=bold,color=blue];

    M34 [shape=record, color=blue, style=bold, label="<f0>బాలకృష్ణ|<f1>బ్రమరాంబ"]
    "M28":f0 -> "M34":f0 [style=bold,color=blue];
    M35 [shape=record, color=blue, style=bold, label="<f0>బాలశంకర్|<f1>ఉమా నాగ మహేశ్వరి"]
    "M28":f0 -> "M35":f0 [style=bold,color=blue];
    M36 [shape=record, color=blue, style=bold, label="<f0>బాల సూర్యప్రకాశ శర్మ|<f1>గీత"]
    "M28":f0 -> "M36":f0 [style=bold,color=blue];

    M37 [shape=record, color=blue, style=bold, label="<f0>పూర్ణ వేంకట సుబ్బారావ్|<f1>విజయలక్ష్మి"]
    "M29":f0 -> "M37":f0 [style=bold,color=blue];
    M38 [shape=record, color=blue, style=bold, label="కృష్ణ శాస్త్రి"]
    "M29":f0 -> "M38" [style=bold,color=blue];
    M39 [shape=record, color=blue, style=bold, label="<f0>అన్నపూర్ణరావ్|<f1>వాణి సత్యవతి"]
    "M29":f0 -> "M39":f0 [style=bold,color=blue];

    M40 [shape=record, color=blue, style=bold, label="<f0>బాల భాస్కర శరభేశ్వర శర్మ|<f1>ఉమాగౌతమి"]
    "M34":f0 -> "M40":f0 [style=bold,color=blue];
    M41 [shape=record, color=blue, style=bold, label="<f0>వీరభద్ర విద్యానాధ శాస్త్రి|<f1>విమల గాయత్రి"]
    "M35":f0 -> "M41" [style=bold,color=blue];
    M42 [shape=record, color=blue, style=bold, label="కృష్ణకాంత్"]
    "M36":f0 -> "M42" [style=bold,color=blue];
  }
custom_mark1
</details>
```
