Needed secrets to run:

kubectl create secret generic jwt-secret --from-literal JWT_KEY=your_jwt_key
kubectl create secret generic stripe-secret --from-literal STRIPE_KEY=your_stripe_key
