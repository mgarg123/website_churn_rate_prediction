# Predicting churn risk score
Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period. . Every user is assigned a prediction value that estimates their state of churn at any given time. This value is based on:

* User demographic information
* Browsing behavior
* Historical purchase data among other information

It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.

# Task
 Prediction of the churn score for a website based on the features provided in the dataset.
 
# Accomplishment 
 After a proper EDA and feature engineering and  used CatBoostClassifier to predict the classes i was able to achieve 76.2% of accuracy on test data. It can be further optimized by further fine tuning the model as their is always a room for the improvement :smile:

# Dataset Description
 
 <table border="1" style="width:500px">
	<tbody>
		<tr>
			<td style="text-align:center; width:157px"><strong>Column name</strong></td>
			<td style="text-align:center; width:327px"><strong>Description</strong></td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">customer_id</td>
			<td style="width:327px">Represents the unique identification number of a customer</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">Name</td>
			<td style="width:327px">Represents the name of a customer</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">age</td>
			<td style="width:327px">Represents the age of a customer</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">security_no</td>
			<td style="width:327px">Represents a unique security number that is used to identify a person</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">region_category</td>
			<td style="width:327px">Represents the region that a customer belongs to&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">membership_category</td>
			<td style="width:327px">Represents the category of the membership that a customer is using</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">joining_date</td>
			<td style="width:327px">Represents the date when a customer became a member&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">joined_through_referral</td>
			<td style="width:327px">Represents whether a customer joined using any referral code or ID</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">referral_id</td>
			<td style="width:327px">Represents a referral ID</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">preferred_offer_types</td>
			<td style="width:327px">Represents the type of offer that a customer prefers</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">medium_of_operation</td>
			<td style="width:327px">Represents the medium of operation that a customer uses for transactions</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">internet_option</td>
			<td style="width:327px">Represents the type of internet service a customer uses</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">last_visit_time</td>
			<td style="width:327px">Represents the last time a customer visited the website</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">days_since_last_login</td>
			<td style="width:327px">Represents the no. of days since a customer last logged into the website</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">avg_time_spent</td>
			<td style="width:327px">Represents the average time spent by a customer on the website</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">avg_transaction_value</td>
			<td style="width:327px">Represents the average transaction value of a customer</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">avg_frequency_login_days</td>
			<td style="width:327px">Represents the no. of times a customer has logged in to the website</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">points_in_wallet</td>
			<td style="width:327px">Represents the points awarded to a customer on each transaction&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">used_special_discount</td>
			<td style="width:327px">Represents whether a customer uses special discounts offered</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">offer_application_preference</td>
			<td style="width:327px">Represents whether a customer prefers offers&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">past_complaint</td>
			<td style="width:327px">Represents whether a customer has raised any complaints&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">complaint_status</td>
			<td style="width:327px">Represents whether the complaints raised by a customer was resolved&nbsp;</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">feedback</td>
			<td style="width:327px">Represents the feedback provided by a customer</td>
		</tr>
		<tr>
			<td style="text-align:center; width:157px">churn_risk_score</td>
			<td style="width:327px">Represents the churn risk score that ranges from 1 to 5</td>
		</tr>
	</tbody>
</table>
