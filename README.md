<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<style>
body {
    background: #1f1f1f;
    font-family: -apple-system, BlinkMacSystemFont, sans-serif;
    display: flex;
    justify-content: center;
    padding: 20px;
}

.calendar {
    background: #2a2a2a;
    border-radius: 20px;
    width: 320px;
    padding: 20px;
    color: #e5e5e5;
    box-shadow: 0 10px 25px rgba(0,0,0,0.4);
}

.header {
    text-align: center;
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 15px;
}

.days, .dates {
    display: grid;
    grid-template-columns: repeat(7, 1fr);
    text-align: center;
}

.days div {
    font-size: 12px;
    opacity: 0.6;
    margin-bottom: 10px;
}

.dates div {
    padding: 10px;
    border-radius: 12px;
    cursor: pointer;
    transition: 0.2s ease;
}

.dates div:hover {
    background: #3a3a3a;
}

.selected {
    background: #444444;
    font-weight: 600;
}
</style>
</head>
<body>

<div class="calendar">
    <div class="header">December 2026</div>
    <div class="days">
        <div>S</div><div>M</div><div>T</div><div>W</div><div>T</div><div>F</div><div>S</div>
    </div>
    <div class="dates">
        <div></div><div></div><div></div><div class="selected">1</div>
        <div>2</div><div>3</div><div>4</div>
        <div>5</div><div>6</div><div>7</div>
        <div>8</div><div>9</div><div>10</div><div>11</div>
        <div>12</div><div>13</div><div>14</div>
        <div>15</div><div>16</div><div>17</div><div>18</div>
        <div>19</div><div>20</div><div>21</div>
        <div>22</div><div>23</div><div>24</div><div>25</div>
        <div>26</div><div>27</div><div>28</div>
        <div>29</div><div>30</div><div>31</div>
    </div>
</div>

</body>
</html>
