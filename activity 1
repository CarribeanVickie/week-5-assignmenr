# Base class
class Superhero:
    def __init__(self, name, power, city):
        self.name = name
        self._power = power      # protected (encapsulation)
        self.city = city

    def introduce(self):
        return f"I am {self.name}, protector of {self.city}!"

    def use_power(self):
        return f"{self.name} uses {self._power}! 💥"


# Child class (inheritance)
class FlyingHero(Superhero):
    def __init__(self, name, power, city, flight_speed):
        super().__init__(name, power, city)   # call parent constructor
        self.flight_speed = flight_speed

    # Polymorphism: override use_power()
    def use_power(self):
        return f"{self.name} soars through the skies at {self.flight_speed} km/h! 🦅"


# Objects
hero1 = Superhero("Shadow Knight", "Invisibility", "Gotham")
hero2 = FlyingHero("Skyblade", "Wind Slash", "Metropolis", 900)

print(hero1.introduce())
print(hero1.use_power())

print(hero2.introduce())
print(hero2.use_power())
