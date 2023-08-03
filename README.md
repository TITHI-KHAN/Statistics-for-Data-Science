# Statistics-for-Data-Science

# Population & Sample

• A population is an entire group that you want to draw conclusions about.

• A sample is a specific group that you will collect data from. The size of the sample is always less than the total size of the population.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/284f6916-42b9-4683-89ba-206c1e931d9d)

# Standard deviation

In statistics, the standard deviation is a measure of the amount of variation or dispersion of a set of values. A low standard deviation indicates that the values tend to be close to the mean of the set, while a high standard deviation indicates that the values are spread out over a wider range.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/b6c43725-e615-4d22-9364-1a1986150533)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/487db1d7-26c7-4940-8ccf-11e523748ddf)

How far is each value from the mean point? 

Ex: Age column. A=[5,7,13,87,56,...]. Here, we have different values, and they have a mean value. Suppose, Mean = 47. 

Then the question is how far is each data point from 47?

Besides, usually, data are not distributed normally. But, there are some data which work like the normal one and kind of similar to the normal distribution. Ex: age, income, spending days in hospital, baby birth wight. etc. These data follow normal distribution.

If data follows normal distribution, then the mean point of the data and the negative side (left), and positive side (right) ->

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/e62c05e3-809d-415f-9c4e-6ff2b363bfd0)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/984b0d37-7d5e-4cdc-ae09-635ad5318fc0)

**-3 sigma to +3 sigma** -> Total in general data distribution. Here, 99.6% data.
**-2 sigma to +2 sigma**-> 95.4% data.
**-1 sigma to +1 sigma** -> 68.2% data out of total data.

The closer the data is to the mean value, the better. In that case, 68.2% data is better but 100-68.2 = 31.8% data gets lost or removed. We cannot remove data like this way. It is not a good practice. 

Normally, we work with 99.6% data. In that case, 0.4% data gets removed and normally, those 0.4% data gets to be considerd as outliers.

However, if we want to increase the number of outliers, then we can consider either -2.5 sigma to +2.5 sigma or -2 sigma to +2 sigma. 

If we consider -2 sigma to +2 sigma, then 4.6% data will be lost (outlier).

If we consider -2.5 sigma to +2.5 sigma, then 2% data will be lost (outlier).

The closer the data is to the mean, the better the result will be. But, if we remove data, then the result of real-life prediction will not be better. So, the less we will remove data, the better. 

*****If there is outlier, then there is a robust way for data scaling such as Robust Scaler, and Logarithmic Transformation.**

**Variance:**

If we square the Standard Deviation, then we will get the Variance.

# What are the properties of normal distributions?

• The mean, median, and mode are exactly the same.

• The distribution is symmetric about the mean—half the values fall below the mean and half above the mean.

• The distribution can be described by two values: the mean and the standard deviation.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/86555a47-d60a-4049-b02d-479242a5dcef)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/abbb251b-8399-472c-a2f0-73758e822e9c)

**Mean** -> It starts from the smaller side and then comes to 0; again starts from bigger side and comes to the smaller side 



• The mean determines where the peak of the curve is centered. Increasing the mean moves the curve right, while decreasing it moves the curve left.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/9d0923c5-9a8d-4716-ac58-ffa10c0b3ba0)

• The standard deviation stretches or squeezes the curve. A small standard deviation results in a narrow curve, while a large standard deviation leads to a wide curve.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/89c29e1f-c747-44be-b88d-1f9a5211694c)

**Normal Distribution:**

• Income Distribution In Economy

• Shoe Size

• Birth Weight

• Spending Days in Hospital

**Normal Distribution of Gaussian Distribution:**

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/8e9834db-c054-491d-a41e-f7e9eda9473a)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/f13da22b-8255-4e14-99c4-70b0308ce28c)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/cf5bf3ff-54be-48ca-9f1c-0c0a1d7001da)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/8facd1b6-5cf2-4a77-8d14-3d55f722f65c)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/9faf3494-d328-4f09-85d0-260690e6a7c8)

# Skewness

Skewness refers to a distortion that deviates from the symmetrical bell curve, or normal distribution, in a set of data. If the curve is shifted to the left or to the right, it is said to be skewed.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/e8d53e0c-9c0a-4e82-a544-96901885f9ab)

How data is mainly distributed, we can visually represent that using Skewness. 

If we consider the median as neutral, then yellow color is **positive skewed** and blue color is **negative skewed**. If the data is distributed equally to the left and right side, then it is called '**Symmetric Distribution**'. In Symmetric Distribution, skewness is 0.

**Median:**

Suppose, we have an age column with range from 10 to 100. Min = 10, Max = 90.

People from 17 to 40 years old are more. So, here, we get more data density, frequency, and count value. 

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/587de41a-095b-467c-bdee-bbe68d0b1248)

If the data of people (25 years old) are high, then ->

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/ff2431b1-7a64-4a0f-8a51-d2ea4c0da301)

From the beginning of range, then density (number of people) is high. Frequency is also high. So, in that place, it will be right skewed because, it is less in the right side. The more we go to the right side, the less the frequency becomes.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/916e2266-bd27-406e-8d44-80411b9d5232)

Normally ->

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/8a653a08-9f63-44f4-9b31-1428e780185b)


# Boxplot

Using boxplot, we can detect outlier. The data which is outside the range of the box, will be considered as outlier (It is far from the mean data. It can be either in the positive side or negative side).

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/ac6f6df7-8a2c-405e-b9d9-6e9b3c6d2b2f)

Typically, any data point that falls below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR is considered an outlier. 

This is a general guideline, and the threshold of 1.5 can be adjusted based on the specific requirements of your analysis or the characteristics of your dataset.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/0940eb25-e928-45e5-8f60-fd11b1561466)

**To create a boxplot, you can follow these steps:**

1. **Gather your dataset**: Collect the numerical data that you want to visualize using a box plot.

2.**Determine the key components**: Identify the minimum, first quartile (Q1), median (Q2), third quartile (Q3), and maximum values of your dataset.

3. **Calculate the interquartile range (IQR)**: Subtract Q1 from Q3 to obtain the IQR.

4. **Identify any outliers**: Determine if there are any values that fall below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR. These values are considered outliers and may be plotted individually as points.

5.**Set up the box plot**: Draw a number line or axis to represent the range of your dataset. Place a box that spans from Q1 to Q3 on the number line. Draw a line within the box to represent the median (Q2).

6. **Add whiskers**: Extend lines, known as "whiskers," from the box to the minimum and maximum values that are not considered outliers.

7. **Plot outliers**: If there are any outliers, plot them individually as points outside the whiskers.

8. **Label and title**: Add appropriate labels to the number line, box, whiskers, and outliers. Provide a title that describes the dataset or the purpose of the box plot.

**Quartile & Percentile:**

The **first quartile (Q1)** corresponds to the **25th percentile**, which means 25% of the data falls below Q1. 

The **second quartile (Q2)** is the median and corresponds to the **50th percentile**, indicating that 50% of the data falls below Q2. 

The **third quartile (Q3)** corresponds to the **75th percentile**, where 75% of the data falls below Q3.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/cf87dedc-c16c-426c-bb46-079be43057d5)

**Construct Boxplot:**

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/c1a9a443-2da6-498d-93ac-ac48e1f8181c)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/b38405a6-6284-4d99-8a08-e921e62c4958)

Here, 20 is an **outlier**. The mean value of 1 to 10 is 5. 20-5=15 difference. It's a huge difference from the mean value. So, 20 is an outlier.

We need **Min, Max, Upper Whisker / Fence, Lower Whisker / Fence, Q1 / Lower Quartile, Q2 / Middle Quartile, and Q3 / Upper Quartile** to draw the boxplot.

Before finding out Q1, we have to sort the data in **ascending order**.

**Q2** = (50/100) * (N+1)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/2ceb5ea0-f1e3-4b24-8500-0780e967ab72)

IQR or Inter Quartile Range : Data which are in the range from Q1 to Q3.

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/83496eda-bede-497a-98a2-21014e642b58)

Data which are outside the Upper Whisker and Lower Whisker are also considered as Outlier.

Boxplot is mostly used in the stock market. 

**Boxplot with matplotlib:**

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/df2f3676-105f-4d78-a786-ded71b16222d)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/5c15af5b-4245-461e-a9d2-b3c88224b506)

Here, fig.ax -> it will take a figure (fig) and it will take a particular axis (ax).

**Boxplot with Seaborn:**

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/69b0aa67-ca0d-454e-ab99-6a5bc4b48311)

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/a7f8ff1d-4be6-40b5-b04a-816eafe4a5fb)

# Histogram

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/aa3e9271-6f2e-4c28-a5ab-436bcca00990)

It visually represents the count value of the data frequency. 

# Z Scores

How many distances standard deviation away a data point is, from the mean value?

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/7e1cc6a4-936e-4a00-8806-c79d5336fbf5)


# Bayesian Neural Network

Bayesian neural network (BNN) combines neural network with Bayesian inference. Simply speaking, in BNN, we treat the weights and outputs as the variables and we are finding their marginal distributions that best fit the data. The ultimate goal of BNN is to quantify the uncertainty introduced by the models in terms of outputs and weights so as to explain the trustworthiness of the prediction.

Here, one layer sends data distribution to another layer where in a **Standard Neural Network**, it sends weight. 

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/80c2826c-6dd4-4112-bc67-b0c8bea76abc)

After that, it uses mean value or standard deviation or variance in the back propagation. Then, it updates it ultimately. 

![image](https://github.com/TITHI-KHAN/Statistics-for-Data-Science/assets/65033964/4c372929-f504-459c-8182-8e1e3f3b5837)

From the above figure, we can easily understand the mean value. Besides, we can also understand the data distribution by the data frequency and bell curve. 

Data can be distributed in many ways.
