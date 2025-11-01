# Class 10 Students Performance Analysis

## ?? Objective
To analyze the academic and co-curricular performance of Class 10 students and identify trends, correlations, and improvement areas.
## Dataset Information
- **File used:** students_class10_basic_dataset.csv  
- **Total records:** 40 students  
- **Attributes:** Marks in subjects, attendance, and activity points  

## ?? Data Cleaning Performed
- Removed missing values (`dropna()`)
- Removed duplicates (`drop_duplicates()`)
- Cleaned column names (lowercase and replaced spaces with underscores)

## ?? Data Analysis Performed
1. Calculated average marks for each subject  
2. Found highest and lowest performing subjects  
3. Checked correlation between subjects  
4. Analyzed the effect of attendance on marks  
5. Identified top and bottom 5 students based on total marks  

## ?? Insights and Observations
- Students performed best in **Geography** and **Science**.  
- **Discipline_10** and **Cultural_Points_20** had the lowest averages.  
- Strong positive correlation observed between **Maths** and **Science** marks.  
- Students with **higher attendance** generally scored better.  
- A few students need support in weak subjects and attendance improvement.  
- Co-curricular activities contribute to better overall discipline and confidence.

##  Conclusion
Most students performed consistently across academic and co-curricular areas.  
The dataset highlights that good attendance and balanced participation lead to improved academic outcomes.  

## ??? Visualizations
- Correlation Heatmap (Subjects)
- Attendance vs Maths Scatter Plot
- Bar Chart: Average Marks per Subject

## Future Work
- Add gender or class-section-wise analysis.  
- Predict student performance using Machine Learning models.
