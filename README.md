# cc_experiment2.3.1
# javascript

var addDigits = function(num) {
    while (num >= 10) {
        let sum = 0;

        while (num > 0) {
            sum += num % 10;
            num = Math.floor(num / 10);
        }

        num = sum;
    }

    return num;
};
