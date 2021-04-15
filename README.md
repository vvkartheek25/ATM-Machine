# ATM-Machine
Bear Robotics Coding Challenge

```
test_bank2 = Bank()
test_bank2.add_entry(123456789, 1234, "checking", 1000)
test_bank2.add_account(123456789, "savings", 1000)
test_bank2.add_entry(987654321, 7321, "checking", 5000)
test_atm2 = Controller(test_bank2, 10000)
cash_bin_over_action = [("See Balance", 0), ("Withdraw", 30000)]
```

Test Invalid Message on Empty ATM -- PASS
Test Success on Valid ATM -- PASS
Test Overdraft handling -- PASS
Test Incorrect Pin Number -- PASS
Test Incorrect Acc Number -- PASS
Test cash bin excess handling -- PASS
Test exiting -- PASS

