# Optimal time for a global meeting

Assuming that every human on the planet is working on the same day, what is the best time of the day to maximize attendance to a global work meeting?

To answer this question, I [used](optimal_meeting_time.ipynb) the inventory of global population by simplified Coordinated Universal Time offset (Crump and Davies 2022). The best time of the day to maximize attendance to a global meeting depends on the duration of the working day. If all humans work 8 hours per day from 9am to 5pm (local time), then the best hour of the day to maximize attendance is 9:00 UTC. This would allow people living in countries from UTC+0 (Europe) to UTC+8 (China) to attend the meeting, but it would exclude people living in the Americas.

![Screenshot 2024-10-02 at 22-04-53 Global-meeting-time_image png at master · sgascoin_Global-meeting-time](https://github.com/user-attachments/assets/6fa7ac49-ce03-48b8-bb55-5725321b0d48)

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Working time duration (hours)</th>
      <th>Available population (millions)</th>
      <th>Optimal time in UTC (hour of the day)</th>
      <th>Working time interval (hour of the day)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>8</td>
      <td>6469.67</td>
      <td>9.0</td>
      <td>(9, 17]</td>
    </tr>
    <tr>
      <td>10</td>
      <td>6723.60</td>
      <td>8.0</td>
      <td>(8, 18]</td>
    </tr>
    <tr>
      <td>12</td>
      <td>6944.53</td>
      <td>10.0</td>
      <td>(7, 19]</td>
    </tr>
    <tr>
      <td>14</td>
      <td>7403.31</td>
      <td>12.0</td>
      <td>(6, 20]</td>
    </tr>
    <tr>
      <td>16</td>
      <td>7664.86</td>
      <td>12.0</td>
      <td>(5, 21]</td>
    </tr>
  </tbody>
</table>
</div>


## References

Crump JA, Davies TM
Towards equitable scheduling of global health teleconferences: a spatial exploration of the world’s population and health by time zone
BMJ Open 2022;12:e056696. doi: 10.1136/bmjopen-2021-056696
