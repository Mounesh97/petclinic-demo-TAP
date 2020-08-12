pipeline{
agent any
stages{
stage ('BUILD') {
steps{
echo "Building Project"
}
}
stage ('Archieve') {
steps{
echo "Archiving Project"
}
}
stage ('BUILD Docker Image'){
steps{
echo "Building Docker"
}
}
stage ('Push Docker Image'){
steps{
echo "Pushing Docker Image"
}
}
stage ('Deploy to Dev'){
steps{
echo "Deploying to Dev Environment"
}
}
}
}
