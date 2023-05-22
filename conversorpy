def convert_length(length, from_unit, to_unit):
    """Converts a length from one unit to another."""
    # Define conversion factors
    factors = {
        'cm': 1,
        'm': 100,
        'in': 2.54,
    }
    # Convert to base unit (cm)
    length_cm = length * factors[from_unit]
    # Convert from base unit to target unit
    length_target = length_cm / factors[to_unit]
    return length_target

length = 10
from_unit = 'cm'
to_unit = 'in'
converted_length = convert_length(length, from_unit, to_unit)
print(f"{length} {from_unit} = {converted_length} {to_unit}")
