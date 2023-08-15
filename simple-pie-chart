import matplotlib.pyplot as plt

# Data
students_enrolled = 1476
students_reported = 926
students_not_reported = students_enrolled - students_reported

labels = ['Reported', 'Not Reported']
sizes = [students_reported, students_not_reported]
colors = ['#4CAF50', '#FFC107']
explode = (0.1, 0)  # explode 1st slice for emphasis

# Plot
plt.figure(figsize=(10, 6))
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.2f%%', shadow=True, startangle=140)

plt.axis('equal')  # Equal aspect ratio ensures that pie is drawn as a circle.
plt.title("Weekly attendance reported in Fall 2022")
plt.show()
