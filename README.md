# Terminal progress bar
A simple progress bar for terminal written in python3.10.
Inspired by https://www.youtube.com/watch?v=x1eaT88vJUA
***
## Parameters
| Name | Description |
| :--- | :--- |
| __total__ (int) | Number of tasks to be completed. |
| __long__ (bool) | True by default, False gives shorter bar, keyword only. |

## Methods
| Name | Parameters | Return | Description |
| :--- | :--- | :--- | :--- |
| __add__ | - | None | Adds one to the number of completed tasks |
| __display__ | __description__ (Optional[str] | None | Displays the bar and completed percentage |

## Requirements
| Name |
| $python3.8+$ |
| $colorama$ |

