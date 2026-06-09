class SundarH:
    def __init__(self):
        self.name           = "Sundar H"
        self.location       = "Tiruvallur, India 🇮🇳"
        self.degree         = "B.E. Mechanical Engineering (2024–2028)"
        self.college        = "Rajalakshmi Engineering College"
        self.cgpa           = 7.02

        self.stack = [
            "Python", "Machine Learning",
            "MATLAB", "AutoCAD"
        ]

        self.currently_learning = [
            "Deep Learning",
            "IoT & Embedded Systems",
            "Advanced ML Algorithms",
            "Cloud Integration for ML"
        ]

        self.fun_fact = (
            "I'm a Football Goalkeeper — "
            "reflexes on the field, "
            "precision in the codebase."
        )

    def motto(self):
        return (
            "Engineer the physical. "
            "Automate the predictable. "
            "Innovate the rest."
        )

me = SundarH()
print(me.motto())