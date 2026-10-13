# NumPy Data Filtering

This project demonstrates how to use NumPy conditions and Boolean indexing to filter student marks based on different thresholds.

## Objectives

- Create a NumPy array of student marks.
- Find marks above a threshold.
- Find marks below a threshold.
- Find marks equal to a threshold.
- Test the filters with different threshold values.

## Technologies Used

- Python
- NumPy
- Jupyter Notebook

## Filtering Operations

- `marks > threshold` — finds values above the threshold.
- `marks < threshold` — finds values below the threshold.
- `marks == threshold` — finds values equal to the threshold.
- `marks[condition]` — Boolean indexing to return only the matching values.

## Dataset

Marks of 10 students:

| Student | Marks |
|---------|------:|
| Arun | 45 |
| Dharani | 82 |
| Kavin | 67 |
| Premi | 90 |
| Sowmini | 38 |
| Rohitha | 75 |
| Keerthana | 58 |
| Yoga | 95 |
| Arjun | 75 |
| Anu | 50 |

## Results

- Marks above 60: `[82 67 90 75 95 75]` (6 students)
- Marks below 50: `[45 38]` (2 students: Arun, Sowmini)
- Marks equal to 75: `[75 75]` (2 students: Rohitha, Arjun)

### Different Thresholds

| Threshold | Above | Below | Equal |
|----------:|------:|------:|------:|
| 50 | 7 | 2 | 1 |
| 60 | 6 | 4 | 0 |
| 75 | 3 | 5 | 2 |
| 90 | 1 | 8 | 1 |

For every threshold, the above, below, and equal counts add up to 10 students.

## Conclusion

This task demonstrates how NumPy Boolean conditions and Boolean indexing make it easy to filter numerical data using different thresholds.
