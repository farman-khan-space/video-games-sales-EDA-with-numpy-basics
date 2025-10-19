| Index | Column Name | Data Type | Description | Missing Count | Missing (%) |
| :--- | :--- | :--- | :--- |  :--- | :--- |
| 0 |`Name` | `string` | The title of the video game. | 2 | ~0.01% |
| 1 |`Platform` | `string` | The console or system the game was released on (e.g., "PS2", "Wii"). | 0 | 0.0% |
| 2 |`Year_of_Release`| `float64` | The year the game was first released. | 269 | ~1.6% |
| 3 |`Genre` | `string` | The style or category of the game (e.g., "Action", "Sports"). | 2 | ~0.01% |
| 4 |`Publisher` | `string` | The company that published and distributed the game. | 54 | ~0.3% |
| 5 |`NA_Sales` | `float64` | Sales in **North America** (in millions of copies). | 0 | 0.0% |
| 6 |`EU_Sales` | `float64` | Sales in **Europe** (in millions of copies). | 0 | 0.0% |
| 7 |`JP_Sales` | `float64` | Sales in **Japan** (in millions of copies). | 0 | 0.0% |
| 8 |`Other_Sales` | `float64` | Sales in the rest of the world (in millions of copies). | 0 | 0.0% |
| 9 |`Global_Sales` | `float64` | Total ***worldwide sales*** (sum of all regions, in millions). | 0 | 0.0% |
| 10 |`Critic_Score` | `float64` | The average score given by professional critics (out of 100). | 8,582 | <span style="color:red;">~51.3%</span> |
| 11 |`Critic_Count` | `float64` | The number of professional critics who gave a score. | 8,582 | <span style="color:red;">~51.3%</span>|
| 12 |`User_Score` | `float64` | The average score given by players/users (out of 10). | 9,129 | <span style="color:red;">~54.6%</span> |
| 13 |`User_Count` | `float64` | The number of players/users who gave a score. | 9,129 | <span style="color:red;">~54.6%</span>|
| 14 |`Developer` | `string` | The studio or company that created the game. | 6,623 | <span style="color:orange;">~39.6%</span> |
| 15 |`Rating` | `string` | The content rating of the game (e.g., "E" for Everyone, "M" for Mature). | 6,769 | <span style="color:orange;">~40.5%</span> |


# Steps of Data analysis
### Loading the vgsales.csv
### Slice the relevent columns
### Clean the cloumns
### Do EDA on those Columns
### Stack the columns into a csv again 
### Export that CSV