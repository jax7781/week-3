# week-3
Scripts for week 3
def calculate_tax(income, tax_rate):
    tax_amount = income * tax_rate
    return round(tax_amount, 2)
income = float(input("Enter your income: "))
tax_rate = 0.15
tax_amount = calculate_tax(income, tax_rate)
print("The calculated tax amount is:", tax_amount)

speed_of_light = 3 * 10**8
seconds_in_a_year = 365 * 24 * 60 * 60
light_year_distance = speed_of_light * seconds_in_a_year
print("The value of a light-year is approximately", light_year_distance, "meters.")

hourly_wage = float(input("Enter the hourly wage: "))
total_regular_hours = float(input("Enter the total regular hours: "))
total_overtime_hours = float(input("Enter the total overtime hours: "))
overtime_pay = total_overtime_hours * 1.5 * hourly_wage
total_weekly_pay = (hourly_wage * total_regular_hours) + overtime_pay
print("The employee's total weekly pay is:", total_weekly_pay)
