# presnomination
<script src="//d3js.org/d3.v3.min.js" charset="utf-8"></script>
<html>
<head>
    <script type="text/javascript" src="http://mbostock.github.com/d3/d3.js"></script>
</head>
<body>
    <div id="viz"></div>
    <script type="text/javascript">

    var sampleSVG = d3.select("#viz")
        .append("svg")
        .attr("width", 100)
        .attr("height", 100);    

    sampleSVG.append("circle")
        .style("stroke", "gray")
        .style("fill", "white")
        .attr("r", 40)
        .attr("cx", 50)
        .attr("cy", 50)
        .on("mouseover", function(){d3.select(this).style("fill", "aliceblue");})
        .on("mouseout", function(){d3.select(this).style("fill", "white");});
    
    </script>
</body>
</html>
