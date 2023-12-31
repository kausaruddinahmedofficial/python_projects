import matplotlib.pyplot as plt

# Define the data
years = range(2014, 2024)
academic_scores = [9, 7, 9, 8, 7, 3, 4, 1, 9, 8]
islamic_scores = [2, 4, 5, 6, 7, 8, 9, 9, 7, 5]
extracurricular_scores = [9, 7, 5, 5, 4, 2, 1, 1, 7, 9]

# Create the line graph
plt.figure(figsize=(10, 6))

plt.plot(years, academic_scores, label='Academic', marker='o', color='blue')
plt.plot(years, islamic_scores, label='Islamic', marker='s', color='green')
plt.plot(years, extracurricular_scores, label='Extracurricular', marker='^', color='orange')

# Add labels and title
plt.xlabel('Year')
plt.ylabel('Score (out of 10)')
plt.title('My last decade at a glance')

# Add legend
plt.legend()

# Add grid lines
plt.grid(True, linestyle='--', linewidth=0.5)

# Rotate x-axis labels for readability
plt.xticks(rotation=45)

# Beautify the graph
plt.tight_layout()

# Save the graph as an image
plt.savefig('my_last_decade.png')

# Show the graph
plt.show()
