class mysyk:
    def __init__(self, aty):
        self.aty = aty
        self.tamak = 50

    def feed(self):
        self.tamak -= 10
        print(f"{self.aty} tamak jep ald ashtygy {self.tamak}")

    def play(self):
        self.tamak -= 10
        print(f"{self.aty} ashtyk indicator {self.tamak}")

pet = mysyk("Багира")
pet.feed()
pet.play()
