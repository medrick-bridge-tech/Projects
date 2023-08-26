<h1>NAME OF GAME</h1>
<hr>
<div>
<ul>
<li><a href="#story">Story</a></li>
<li><a href="#weapons">Weapons</a></li>
<li><a href="#enemies">Enemies</a></li>
<li><a href="#map">Map</a></li>
<li><a href="#dungeons">Dungeons</a></li>
<li><a href="#items">Items</a></li>
<li><a href="#shop">Shop</a></li>
<li><a href="#todo">To do ...</a></li>
</ul>
</div>

<hr>

<div id="story">
<!--
    <p></p>
    <p><b>2030</b>, Super power governments destroyed after <b>World War III</b>. You were a simple soldier in your country squad, but now there is no squad. So you are free to act as a free soldier and make your own squad.</p>
    <p>In your way: </p>
    <ul>
        <li>Kill other soldiers and take their money.</li>
        <li>Help people and as a reward take them to your shelter.</li>
        <li>Buy better items ... Better items make you better soldier.</li>
        ...
    </ul>
-->
    <h3>Story</h3>
    <p>General Bin, sent you to a mission in Derocsid area, which is high protected by enemies. Find documents, steal it and get out of area.</p>
    <p>In your way: </p>
    <ul>
        <li>Kill other soldiers and take their money.</li>
        <li>Buy better items ... Better items make you better soldier.</li>
    </ul>
</div>

<hr>

<div id="weapons">
<h3>Weapons</h3>
<table>
<tr>
    <th>Name</th>
    <th>Damage</th>
    <th>Fire Rate</th>
</tr>
<tr>
    <td>Pistol</td>
    <td>10</td>
    <td>1</td>
</tr>
<tr>
    <td>Assault</td>
    <td>20</td>
    <td>0.3</td>
</tr>
<tr>
    <td>Shotgun</td>
    <td>30</td>
    <td>2</td>
</tr>
<tr>
    <td>Rifle</td>
    <td>50</td>
    <td>3</td>
</tr>
</table>
</div>

<hr>

<div id="enemies">
<h3>Enemies</h3>
<table>
<tr>
    <th>Name</th>
    <th>Damage</th>
    <th>Health</th>
    <th>Value</th>
</tr>
<tr>
    <td>Soldier-Lvl1</td>
    <td>5</td>
    <td>10</td>
    <td>1</td>
</tr>
<tr>
    <td>Soldier-Lvl2</td>
    <td>10</td>
    <td>20</td>
    <td>5</td>
</tr>
<tr>
    <td>Soldier-Lvl3</td>
    <td>30</td>
    <td>50</td>
    <td>15</td>
</tr>
<tr>
    <td>FireWall</td>
    <td>50</td>
    <td>200</td>
    <td>50</td>
</tr>
</table>
</div>

<hr>

<div id="map">
<h3>Maps</h3>
<img src="map/1.png">
<img src="map/2.png">
<img src="map/3.png">
</div>

<hr>

<div id="dungeons">

</div>

<hr>

<div id="items">
<h3>Items</h3>
<table>
<tr>
    <th>Name</th>
    <th>Damage</th>
    <th>Speed</th>
</tr>
<tr>
    <td>Land Mine</td>
    <td>100</td>
    <td>---</td>
</tr>
<tr>
    <td>Armor</td>
    <td>---</td>
    <td>---</td>
</tr>
<tr>
    <td>Key</td>
    <td>---</td>
    <td>---</td>
</tr>
<tr>
    <td>Chest</td>
    <td>---</td>
    <td>---</td>
</tr>
<tr>
    <td>Coin</td>
    <td>---</td>
    <td>---</td>
</tr>
<tr>
    <td>Car</td>
    <td>5</td>
    <td>20</td>
</tr>
<tr>
    <td>Helicopter</td>
    <td>1-5</td>
    <td>40</td>
</tr>
<tr>
    <td>AirPlane</td>
    <td>1000</td>
    <td>50</td>

</tr>
<tr>
    <td>Light Tank</td>
    <td>20</td>
    <td>15</td>
</tr>
<tr>
    <td>Medium Tank</td>
    <td>50</td>
    <td>10</td>
</tr>
<tr>
    <td>Heavy Tank</td>
    <td>100</td>
    <td>5</td>
</tr>
</table>
</div>

<hr>

<div id="shop">
<h3>Shop</h3>
<table>
<tr>
    <th>Name</th>
    <th>Products</th>
    <th>Price</th>
</tr>
<tr>
    <td>Gigili Bomb</td>
    <td>Land Mine</td>
    <td>1</td>
</tr>
<tr>
    <td rowspan = "4">Antonio Weapon</td>
    <td>Pistol</td>
    <td>100</td>
</tr>
<tr>
    <td>Assault</td>
    <td>200</td>
</tr>
<tr>
    <td>Shotgun</td>
    <td>350</td>
</tr>
<tr>
    <td>Rifle</td>
    <td>500</td>
</tr>
<tr>
    <td rowspan="6">Chumbucket Garage</td>
    <td>Car</td>
    <td>1000</td>
</tr>
<tr>
    <td>Helicopter</td>
    <td>5000</td>
</tr>
<tr>
    <td>Airplane</td>
    <td>50000</td>
</tr>
<tr>
    <td>Light Tank</td>
    <td>2500</td>
</tr>
<tr>
    <td>Medium Tank</td>
    <td>7500</td>
</tr>
<tr>
    <td>Heavy Tank</td>
    <td>12500</td>
</tr>
</table>
</div>

<hr>

<div id="Steps">
<p><b>Weapons: </b> pistol -> ammo </p>
<p><b>Item:</b> armor, mine, key </p>
<p><b>Enemy:</b><ul><li>Fast: less health</li><li>Slow: tank</li></ul></p>
<p><b>Map:</b> 40x40</p>
<p><b>Screen:</b> 10x10</p>
<p><b>Box:</b> chest<p>
<p><b>enemies:</b><ul><li>10% key</li><li>90% money [10...25]</li></ul></p>
<p><b>Goal:</b> Find documents and reach destination</p>
</div>

<div id="todo">
<h3>To Do ...</h3>
<input type="checkbox"><label>Add dungeons</label>

</div> 