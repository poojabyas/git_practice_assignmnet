# git_practice_assignmnet
num = 11
function identifyPrime(num) {
     let count = 0;

    for (let i = 0; i <= num; i++) {
        if (num % i === 0) {
            count++;
        }
    }

    if (count = 1) {
        console.log("Yes");
    } else {
        console.log("No");
    }

}
