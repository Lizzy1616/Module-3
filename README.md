# Module-3
Insuranc
class Policyholder: 
  def __init__(self, name, policy_number, is_active=True):
    self.name = name
    self.policy_number = policy_number
    self.is_active = is_active
  def suspend(self):
    self.is_active = False
  def reactivate(self):
    self.is_active = True
class Product:
def __init__(self, name, price, is_active=True):
    self.name = name
    self.price = price
    self.is_active = is_active
def update_price(self, new_price):
    self.price = new_price
def suspend(self):
self.is_active = False
class Payment: 
    def process_payment(self, amount): 
    # Process payment logic here
    print(f"Payment processed: ${amount}")
    def send_reminder(self):
    # Send payment reminder logic here
    print("Payment reminder sent")
    def apply_penalty(self):
    # Apply penalty logic here 
    print("Penalty applied")
# Policyholder demonstration
policyholder1 = Policyholder("Alice", "POL001")
policyholder2 = Policyholder("Bob", "POL002")

product1 = Product("Life Insurance", 100)
product2 = Product("Car Insurance", 50)
payment_processor = Payment()
policyholder1.suspend()
product1.suspend()
print(f"Policyholder: {policyholder1.name}, Policy Number: {policyholder1.policy_number}, Active: {policyholder1.is_active}")
print(f"Policyholder: {policyholder2.name}, Policy Number: {policyholder2.policy_number}, Active: {policyholder2.is_active}")
payment_processor.process_payment(100)
payment_processor.send_reminder()
payment_processor.apply_penalty()
