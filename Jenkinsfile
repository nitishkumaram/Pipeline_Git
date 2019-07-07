// S2L26_Pipeline>Options>OverrideIndexTriggers
// pipeline{
//     agent any

//     options{
//         timestamps()
//         overrideIndexTriggers(true)
//     }
//     stages{
//         stage('Build'){
//             steps{
//                 echo "====++++Hello World 5 ++++===="
//             }
//         }
//     }
// }

// S2L28_Pipeline>Options>CheckoutToSubdirectory
pipeline{
    agent any

    options{
        checkoutToSubdirectory('someSuBDir')
    }
    stages{
        stage('Build'){
            steps{
                echo "====++++Hello World++++===="
            }
        }
    }
}