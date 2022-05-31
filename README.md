# Terminal progress bar
A simple progress bar for terminal written in python3.10.2

Inspired by a [YouTube video by NeuralNine](https://www.youtube.com/watch?v=x1eaT88vJUA).
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
| __display__ | __description__ (Optional[str]) | None | Displays the bar and completed percentage. Displays "Task: ..." if description is given, otherwise "N/A". |

## Requirements
| Name |
| :-- |
| [python3.8+](https://www.python.org/) |
| [colorama](https://pypi.org/project/colorama/) |

## Usage
```py
from progressbar.ProgressBar import ProgressBar
pb = ProgressBar(100)
...
pb.add()
pb.display()
```
