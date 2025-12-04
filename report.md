#  Social Anxiety Analysis (EDA)

## Executive Summary

This report presents an exploratory data analysis (EDA) focusing on the
social, behavioral, physiological, and lifestyle factors associated with
social anxiety. The findings indicate that variables such as alcohol
consumption, stress level, heart rate, sleep quality, physical activity,
diet quality, and therapy sessions show the strongest relationships with
the presence of social anxiety.

------------------------------------------------------------------------

## 1. Alcohol Consumption

-   After Winsorizing, the distribution became more reasonable but
    remains right-skewed.
-   On average, anxious individuals consume more alcohol.
-   Q-Q plot confirms non-normality.
-   Boxplot highlights a clear difference between the two groups.

**Insight:**\
Higher alcohol consumption is associated with an increased likelihood of
social anxiety.

------------------------------------------------------------------------

## 2. Stress Level

-   Even after adjusting outliers, the distribution remains skewed.
-   Anxious individuals consistently show higher stress levels.
-   Shapiro test confirms non-normality.

**Insight:**\
Stress is one of the strongest behavioral predictors of social anxiety.

------------------------------------------------------------------------

## 3. Heart Rate

-   Distribution is right-skewed, with most values between 60--120 bpm.
-   Anxious individuals generally have higher heart rates.
-   Q-Q and boxplots clearly confirm this difference.

**Insight:**\
Elevated heart rate is a strong physiological marker of anxiety.

------------------------------------------------------------------------

## 4. Smoking

-   Heatmap, grouped bar plots, and stacked charts indicate that anxious
    individuals have a higher likelihood of smoking.

**Insight:**\
Smoking is associated with anxiety, though it is not a stand-alone
determinant.

------------------------------------------------------------------------

## 5. Family History of Anxiety

-   A significantly higher proportion of anxious individuals report a
    family history of anxiety.

**Insight:**\
Genetic or family-based predispositions play an important role.

------------------------------------------------------------------------

## 6. Breathing Rate

-   Breathing rate shows a strong positive correlation with anxiety.

------------------------------------------------------------------------

## 7. Sweating Level

-   Higher sweating levels correlate with higher social anxiety.
-   Anxious individuals tend to exhibit greater physiological arousal.

------------------------------------------------------------------------

## 8. Dizziness

-   No meaningful or statistically significant relationship observed.
-   Very weak correlation---can be ignored in modeling.

------------------------------------------------------------------------

## 9. Medication Use

-   Slightly higher medication usage among anxious individuals.
-   Association exists but the effect is weak.

------------------------------------------------------------------------

## 10. Therapy Sessions

-   Number of therapy sessions per month shows a strong negative
    correlation with anxiety.
-   Individuals with higher anxiety tend to require more therapy.

------------------------------------------------------------------------

## 11. Recent Major Life Event

-   Individuals who recently experienced a major life event are much
    more likely to have social anxiety.

**Insight:**\
Recent stressful life events strongly increase risk of social anxiety.

------------------------------------------------------------------------

## 12. Diet Quality

-   People with poorer diet quality tend to show higher anxiety levels.
-   After binning into "Good" vs. "Poor" diet, the difference becomes
    clearer.

------------------------------------------------------------------------

## 13. Self-Reported Anxiety Level

-   Individuals scoring 1--6 on self-reported anxiety were all socially
    anxious.
-   Those scoring 7--10 had almost no social anxiety.

**Insight:**\
Self-perception of anxiety correlates strongly with social anxiety
classification.

------------------------------------------------------------------------

## 14. Age

-   People under age 40 show higher rates of social anxiety.
-   Mann--Whitney test confirms significance.

------------------------------------------------------------------------

## 15. Gender

-   No meaningful differences across Male, Female, Other categories.

------------------------------------------------------------------------

## 16. Occupation

-   No statistically significant relationship between occupation type
    and social anxiety.

------------------------------------------------------------------------

## 17. Sleep Hours

-   Individuals with short sleep (0--6 hours) show much higher anxiety.
-   Normal sleep patterns correlate with lower anxiety.

------------------------------------------------------------------------

## 18. Physical Activity (Weekly Hours)

-   Individuals with \<2 hours/week of physical activity show much
    higher anxiety.
-   In the "High Activity" group, anxiety prevalence is nearly zero.

------------------------------------------------------------------------

# Key Takeaways

-   Strongest predictors of social anxiety:\
    stress level, heart rate, sleep duration, physical activity, diet
    quality, recent life events\
-   Moderate signals:\
    smoking, sweating, breathing rate, medication use\
-   Weak or no effect:\
    gender, occupation, dizziness

------------------------------------------------------------------------

# Recommendations

-   Increase physical activity\
-   Improve sleep quality\
-   Adopt a healthier diet\
-   Stress management programs\
-   More attention to those with family history of anxiety\
-   Psychological therapy for high-risk groups

------------------------------------------------------------------------

# Next Steps

-   Build predictive models for social anxiety\
-   Explore variable interactions\
-   Cluster individuals based on behavioral and physiological profiles
