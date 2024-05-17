# imports
import pandas as pd
import random as rand
# staff info (put your name here)
staff_name    = "Ruthvi Lohar"
staff_title   = "Customer Relationship Manager"
staff_company = "DAT-5322 Introduction to Python Programming"
# customer info
customer_data = [  ['Mary', 'dining room tables', 'financing'],
                   ['patrick', 'area rugs', 'return policy'],
                   ['gonzalo', 'dining room tables', 'return policy'],
                   ['UNKNOWN', 'coffee tables', 'in-home assembly'],
                   ['richard', 'sofas', 'free shipping'],
                   ['UNKNOWN', 'dining room tables', 'in-home assembly'],
                   ['tiM', 'sofas', 'return policy'],
                   ['keenan', 'area rugs', 'financing'],
                   ['UNKNOWN', 'area rugs', 'financing'],
                   ['dana', 'bookcases', 'customization'],
                   ['lauren', 'bookcases', 'customization'],
                   ['karen', 'sofas', 'in-home assembly'],  ]


# approved email subject lines
subjects    = [  "people will compliment",                 
                 "on our site are just WOW!",              
                 "you *gotta* see.",                       
                 "handpicked for you!",                    
                 "- Just for you, we rounded up our best", 
                 "we can barely keep in stock",            
                 "we found for you.",                      
                 "at a great price.",                      
                 "we think you will love",  ]


# approved hooks
hook_msg = [  "FREE Shipping",
              "Financing at 0% Interest",
              "In-Home Assembly for just $10",
              "A 30 Day Return Policy with No Strings Attached",
              "Discounted Pricing on Tailoring and Customizations",  ]



# approved openings
opening = [  f"We noticed your interest in our ",
             f"I'm glad you were checking out our ",
             f"You have excellent taste in ",  ]


# approved promotions
promotion = [
    f"Order within the next 18 hours and get ",
    f"Order one today and get ",
    f"Your order qualifies for ",  ]


# approved promotion code
promotion_code = ["!\nJust use the promotion code PYTHON!",
                  "!\nTake advantage with the promo code JUPYTER!",
                  "!\nUse the code ANACONDA during checkout to take advantage!"]

art = [
"""                       
      /~~~~~~~~~~~~~~~~\   
     /~ ()  ()  ()  () ~\  
    (_)================(_) 
     |__________________| 
""",
"""
    ____  
   /    \ 
  /______\
     ||   
     ||   
     ||   
     ||   
    _||_  
""",
"""                     
      /~~~~~~~~\  
     /~ () ()  ~\ 
    (_)========(_)
     I|________|I
"""
]
# defining a personalized email function
def dynamic_email():
    """
    This is a dynamic email generator. It takes no arguments, but the
    following data is required for it to work (should be defined globally):
    
    Note: Defined globally means that these should be defined outside of the
          body of the function. This has been done for you in the cells above.
    
    category       | str | recommended product category
    subject        | str | subject line message
    name           | str | name of a customer
    opening        | str | opening sentence in the body of the email
    promotion      | str | promotional sentence in the email
    hook           | str | mkting hook; part of the promotional sentence
    promotion_code | str | the code for customers to access their promotion
    """
    
    # character length
    print('-' * 40)
    
    
    # character length
    print('-' * 40)
    
    
    # email body
    print(f"""


""")

    # character length
    print('-' * 40, "\n\n")
    # Tip: You should use a for loop to generate each email
# START YOUR LOOP HERE
    
    # Make sure to indent the body of your loop!
    
    
    # Keep this in the body of the loop.
    dynamic_email()
    
