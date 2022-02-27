# Amazon_Vine_Analysis

## Project Overview:
The purpose of the project is use Amazon Vine program written reviews by paid members, and help companies like SellBy that pay a small fee to use the product review provided by Amazon Vine, who are then required to publish a review.

## Results:
The dataset extraction was of Furniture reviews from s3.amazonaws.com, transformed with Google Colaboratory pySpark, and then loaded into PostgreSQL tables.

 - PostgreSQL Tables
 
    ![PostgreSQL](https://user-images.githubusercontent.com/92836648/155860674-bbafdbd6-0dd0-4e5a-b977-49a10897c50e.png)  

  - Customers Table

    ![customers_table](https://user-images.githubusercontent.com/92836648/155860675-d6ff3f6c-beaa-4e98-bddf-2062983bef73.png)

  - Products Table

    ![products_table](https://user-images.githubusercontent.com/92836648/155860676-4d912c43-a919-4ec3-bcc9-ae839d00e4a9.png)

  - Review ID Table

    ![review_id_table](https://user-images.githubusercontent.com/92836648/155860677-5cb953b9-b27e-43b0-a2fb-b6f94b716602.png)

  - Vine Table

    ![vine_table](https://user-images.githubusercontent.com/92836648/155860678-f1631629-78f1-4a9a-bca7-e72b1c313c01.png)
    
  - Vine Data Analysis

    ![Vine_analysis_results](https://user-images.githubusercontent.com/92836648/155860679-f5a60704-3e42-47ca-9d9e-0c3759ba8342.png)
    
    - Total count of Vine (Paid) and non-Vine (Unpaid) reviews.
       - Paid = 136
       - Unpaid = 18019

    - Total count of Vine (Paid) and non-Vine (Unpaid) with 5-star reviews.
       - Paid = 74
       - Unpaid = 8482

    - Total percentage of Vine (Paid) and non-Vine (Unpaid) with 5-star reviews.
       - Paid = 54%
       - Unpaid = 47%

## Summary:
Based on the analysis review data has majority bais of review from non-Vine (Unpaid) compared to Vine (Paid), and the dateset of 5-star reviews indicates almost equal percentage dispite product review count.

I would expand the analysis through the rest of the star ratings and compare the outcome for bias review.









