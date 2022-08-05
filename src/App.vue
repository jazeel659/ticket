<template>
  <div class="container">
    <div class="circle"></div>

    <div class="inner border">
      <div>
        <span>JMB</span>
        <span>Jambi</span>
      </div>
      <div>
        <span>✈</span>
      </div>
      <div>
        <span>JKT</span>
        <span>Jakarta</span>
      </div>
    </div>
    <div class="inner">
      <div>
        <span>1 May</span>
        <span>Date</span>
      </div>
      <div>
        <span>08:00 AM </span>
        <span>Departure time</span>
      </div>
      <div>
        <span>23</span>
        <span> Number</span>
      </div>
    </div>
    <div class="circle"></div>
  </div>
  <div class="container blue">
    <div class="circle"></div>

    <div class="inner border">
      <div>
        <span>JMB</span>
        <span>Jambi</span>
      </div>
      <div>
        <span>✈</span>
      </div>
      <div>
        <span>JKT</span>
        <span>Jakarta</span>
      </div>
    </div>
    <div class="inner">
      <div>
        <span>1 May</span>
        <span>Date</span>
      </div>
      <div>
        <span>08:00 AM </span>
        <span>Departure time</span>
      </div>
      <div>
        <span>23</span>
        <span> Number</span>
      </div>
    </div>
    <div class="circle"></div>
  </div>
</template>
<style >
* {
  margin: 0;
  padding: 0;
}
#app {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  row-gap: 20px;
  justify-content: center;
  align-items: center;
}
.container {
  background-color: #32a19be1;
  width: 400px;
  height: 170px;
  display: flex;
  flex-direction: column;
  color: white;
  font-family: sans-serif;
  border-radius: 15px;
  position: relative;
}
.container.blue {
  background-color: rgb(14, 73, 139);
}
.container .inner.border {
  border-bottom: 2px dashed white;
}
.inner {
  display: flex;
  justify-content: space-between;
  flex: 1;
  align-items: center;
  margin: 0px 12px;
}

.inner div {
  display: flex;
  flex-direction: column;
  /* row-gap: 6px; */
  text-align: center;
}
.inner div:first-child {
  text-align: left;
}
.inner div:last-child {
  text-align: right;
}
.inner div span:first-child {
  margin-bottom: 6px;
}

.circle {
  height: 20px;
  width: 20px;
  background-color: white;
  border-radius: 10px;
  position: absolute;
  top: 50%;
  transform: translateY(-10px);
}
.container .circle:first-child {
  left: -10px;
}
.container .circle:last-child {
  right: -10px;
}
</style>