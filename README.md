# ketlleclass Kettle:
    def __init__(self, brand, capacity, color, material):
        self.brand = brand
        self.capacity = capacity
        self.color = color
        self.material = material

    def display_information(self):
        print("Kettle Information:")
        print(f"Brand: {self.brand}")
        print(f"Capacity: {self.capacity} liters")
        print(f"Color: {self.color}")
        print(f"Material: {self.material}")


# Example usage
if __name__ == "__main__":
    # Create a kettle object
    my_kettle = Kettle(brand="ExampleBrand", capacity=1.7, color="Silver", material="Stainless Steel")

    # Display information about the kettle
    my_kettle.display_information()
