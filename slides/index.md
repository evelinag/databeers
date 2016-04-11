- title : Exploring the Star Wars universe
- description : DataBeers@London
- author : Evelina Gabasova
- theme : white
- transition : none

***

- data-background : images/cancer-unit.jpg

<table>
<tr>
  <td class="noborder" style="width:50%;">

## <div class="white">Evelina Gabasova</div>
### <div class="white">@evelgab</div>
### <div class="white">evelinag.com</div>

<br />
<br />
<div class="white">MRC Cancer Unit </div>
<br />
<div class="white">University of Cambridge</div>
</td>
  <td class="noborder" style="width:50%;"></td>
</tr>
</table>

' Hello, I'm Evelina Gabasova

---

- data-background : images/tcga-dna.jpg

' During the day, I do bioinformatics and computational biology,
' researching mechanisms of early carcinogenesis at Cambridge
' University - I deal with DNA, genes, proteins etc...
' It's a very important work, we work on pancreatic cancer which 
' one of the least understood types of cancer. It's very hard to treat
' and mortality hasn't improved much over the last 10 years, so it's a big 
' and important challenge. We use quite a lot of methods, based on 
' statistics, machine learning and network analysis. 
' But biology is complex and sometimes it's a bit too much...

---

- data-background : images/pathways.png

' do you know the feeling? So because I love working with data, outside
' of work I like to play with other datasets, datasets that are
' probably less useful...

---

- data-background : images/intro-databeers-noloop.gif

---

- data-background : #550080

# <div class="sw"> star wars </div>
## Social network

' Enter the Star Wars social network

------

- data-background : #f2a063

![script structure](images/script-example.png)

' This structure is highly formalised, names have to be in boldface and centered etc.
' This is easy to parse if you write a program to do this

----

- data-background : white

![](images/network-relations.png)

-----

- data-background : images/itsatrap3.gif

---

- data-background : images/r2d2beeps-loop3.gif

--------

- data-background : #f2a063


![R2-D2](images/artoo.png)

--------

- data-background : #f2a063


![Chewbacca](images/chewie.png)

---

- data-background : #550080

## Number of *common* mentions

# ⬇

## Number of interactions

--------

- data-background : images/ewoks.gif

---

- data-background : images/networks/full_network-darth-vader.png

<a href="images/networks/interactions-merged.html" style="color: transparent;"> Big link to full network <br /> Big link to full network <br />Big link to full network </a>

----------

### <div class="sw">a new hope </div> 

<a href="images/networks/episode4-interactions.html"><img src="images/networks/episode4.png" style="height:600px"/> </a>

----------

### <div class="sw">the phantom menace</div>

<a href="images/networks/episode1-interactions.html"><img src="images/networks/episode1.png" style="height:600px"/> </a>

----------

### <div class="sw">the force awakens</div>

<a href="images/networks/episode7-interactions.html"><img src="images/networks/episode7_network.png" style="height:600px"/> </a>


---

### <div class="sw"> Size </div>

<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Episode 1"}, {"v": 38}]}, {"c" : [{"v": "Episode 2"}, {"v": 33}]}, {"c" : [{"v": "Episode 3"}, {"v": 25}]}, {"c" : [{"v": "Episode 4"}, {"v": 22}]}, {"c" : [{"v": "Episode 5"}, {"v": 21}]}, {"c" : [{"v": "Episode 6"}, {"v": 20}]}, {"c" : [{"v": "Episode 7"}, {"v": 27}]}]});
    var options = {"colors":["#3bc4c4"],"hAxis":{"title":"Number of characters","viewWindowMode":"explicit","viewWindow":{"max":40,"min":0}},"legend":{"position":"none"},"title":"Number of characters","width":1000,"height":550} 
    var chart = new google.visualization.BarChart(document.getElementById('793fedd1-18b7-4674-bbd9-333211512707'));
    chart.draw(data, options);
}
</script>
<div id="793fedd1-18b7-4674-bbd9-333211512707" style="width: 800px; height: 600px;"></div>

-----

### <div class="sw"> Density </div>

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Episode 1"}, {"v": 19.203413940256}]}, {"c" : [{"v": "Episode 2"}, {"v": 19.1287878787879}]}, {"c" : [{"v": "Episode 3"}, {"v": 25.296442687747}]}, {"c" : [{"v": "Episode 4"}, {"v": 28.5714285714286}]}, {"c" : [{"v": "Episode 5"}, {"v": 26.1904761904762}]}, {"c" : [{"v": "Episode 6"}, {"v": 31.5789473684211}]}, {"c" : [{"v": "Episode 7"}, {"v": 26.2108262108262}]}]});
    var options = {"colors":["#c43b80"],"hAxis":{"title":"Density (%)","viewWindowMode":"explicit","viewWindow":{"max":35,"min":15}},"legend":{"position":"none"},"title":"Network density","width":1000,"height":550}
    var chart = new google.visualization.BarChart(document.getElementById('526513e7-b223-41f2-8ba0-0008433196f8'));
    chart.draw(data, options);
}
</script>
<div id="526513e7-b223-41f2-8ba0-0008433196f8" style="width: 800px; height: 600px;"></div>

--------

### <div class="sw"> Clustering Coefficient </div>

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Episode 1"}, {"v": 0.447572132301196}]}, {"c" : [{"v": "Episode 2"}, {"v": 0.486666666666667}]}, {"c" : [{"v": "Episode 3"}, {"v": 0.498947368421053}]}, {"c" : [{"v": "Episode 4"}, {"v": 0.559808612440191}]}, {"c" : [{"v": "Episode 5"}, {"v": 0.604651162790698}]}, {"c" : [{"v": "Episode 6"}, {"v": 0.656992084432718}]}, {"c" : [{"v": "Episode 7"}, {"v": 0.588387096774194}]}]});
    var options = {"hAxis":{"title":"Clustering coefficient"},"legend":{"position":"none"},"title":"Clustering coefficient (transitivity)","width":1000,"height":550} 
    var chart = new google.visualization.BarChart(document.getElementById('c7a96a91-f091-4462-b2fd-2ce7d06df07b'));
    chart.draw(data, options);
}
</script>
<div id="c7a96a91-f091-4462-b2fd-2ce7d06df07b" style="width: 800px; height: 600px;"></div>

' How many of your friends in the network are also friends with each other
' What it means in terms of the story

---

### <div class="sw"> Centrality </div>

<small>
<table>
<tr>
  <td class="noborder" style="padding-right: 100px">

| | Name | Degree |
|---|-----|-----|
| 1. | POE | 16 |
| 2. | FINN | 14 |
| 3. | HAN | 14 |
| 4. | CHEWBACCA | 12 |
| 5. | BB-8 | 12 |

</td>
  <td class="noborder">

| | Name | Betweenness |
|---|-----|-----|
1. | POE | 97.2 |
2. | KYLO REN | 71.9 |
3. | REY | 38.7 |
4. | BB-8 | 29.1 |
5. | FINN | 26.8 |

</td>
</tr>
</table>
</small>

---

- data-background : images/poe_dancing.gif

---

- data-background : images/obi-wan-noloop.gif

---

- data-background : images/cell-betweenness.jpg


---

- data-background : images/kyloapproves-loop3.gif

---

- data-background : images/kylo.gif

<table>
<tr>
  <td class="noborder" style="width:50%;"></td>
   <td class="noborder" style="width:50%;">

## <div class="white">Evelina Gabasova</div>
<div class="white">@evelgab </div><br />
<div class="white">github.com/evelinag</div>
</td> 
</tr>
</table>

