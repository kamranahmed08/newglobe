# newglobe
This analysis is based on data from Bridge Kenya programme which operates in 111 schools, in 7 provinces across 31 regions in Kenya. We have anonymized data for ~13,000 pupils from grades 1-5 from the end of an undisclosed school term in the past five years. (Note that each school year has three terms, and they consist of ~3-3.5 months each).

The data set contains the following files:
● “Lesson completion”: file provided at the teacher level, meaning that there is a unique row for each teacher. The file contains the grade that each teacher teaches, and the average lesson completion rate over the term of interest.
● “Pupil attendance”: file provided at the pupil level (that means that there is a unique row for each pupil). This file includes the unique school ID, unique pupil ID, the pupil’s grade, the attendance records, and the present records.
○ The attendance records means the total number of times that a pupil’s teacher took attendance.
○ The present records means the total number of times that a pupil was present, out of the attendance
records.
● “Pupil scores”: file provided at the pupil*subject level (that means that there are more than one row per pupil).
This file includes the unique school ID, unique pupil ID, the pupil’s grade, the subject for this assessment, and
the score obtained in this assessment.
● “School information”: file provided at the school-level. It includes the region and province where each school is
located, the unique school ID, and the “treatment status” (yes/no) for a given tutoring program.
