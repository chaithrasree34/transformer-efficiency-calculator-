# Transformer Efficiency Calculator

print("TRANSFORMER EFFICIENCY CALCULATOR")
print("---------------------------------")

# Input values
V1 = float(input("Enter primary voltage (V): "))
I1 = float(input("Enter primary current (A): "))
V2 = float(input("Enter secondary voltage (V): "))
I2 = float(input("Enter secondary current (A): "))

# Calculate input and output power
input_power = V1 * I1
output_power = V2 * I2

# Calculate losses
losses = input_power - output_power

# Calculate efficiency
efficiency = (output_power / input_power) * 100

# Display results
print("\n--- Transformer Results ---")
print(f"Input Power       = {input_power:.2f} W")
print(f"Output Power      = {output_power:.2f} W")
print(f"Power Loss        = {losses:.2f} W")
print(f"Transformer Efficiency = {efficiency:.2f}%")# transformer-efficiency-calculator-