# D3-chart


![image](https://user-images.githubusercontent.com/90889565/133732572-3f66b902-6812-4767-8f82-50eb919b884e.png)


var line = d3.line()
  .x(d => this.xScale(d.date))
  .y(d => this.yScale(d.price));




{
  end: "00002",
  id: "1",
  name: "met1",
  parentId: "",
  start: "00001",
  type: "mission phase"
}
{
  end: "00002",
  id: "2",
  name: "met2",
  parentId: "1",
  path: ["met1/met2"],
  start: "00001",
  type: "mission phase"
}
{
  end: "00002",
  id: "3",
  name: "met2-1",
  parentId: "2",
  path: ["met1/met2/met2-1"],
  start: "00001",
  type: "mission phase"
}
{
  end: "00002",
  id: "4",
  name: "met2-2",
  parentId: "2",
  path: ["met1/met2/met2-2"],
  start: "00001",
  type: "mission phase"
}
{
  end: "00002",
  id: "5",
  name: "met2-3",
  parentId: "2",
  path: ["met1/met2/met2-3"],
  start: "00001",
  type: "mission phase"
}


![image](https://user-images.githubusercontent.com/90889565/135567108-3360ef9a-5126-420f-abc9-25926f2f1545.png)
