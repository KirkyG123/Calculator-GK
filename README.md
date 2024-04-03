# Calculator-GK
This Repo is for my calculator project in fulfilment of Week 8 of The Skills Network Level 3 Software development Skills Bootcamp.
import unittest

class TestCalculator(unittest.TestCase):
    
    def test_addition(self):
        result = 5 + 7
        self.assertEqual(result, 12)

    def test_division(self):
        result = 20 / 4
        self.assertEqual(result, 5)

    def test_subtraction(self):
        result = 15 - 8
        self.assertEqual(result, 7)

    def test_multiplication(self):
        result = 6 * 9
        self.assertEqual(result, 54)

if __name__ == '__main__':
    unittest.main()
