var general_app = angular.module('anveshak',[]);
general_app.config(['$httpProvider','$interpolateProvider',function($httpProvider,$interpolateProvider){
	$httpProvider.defaults.useXDomain = true;
	delete $httpProvider.defaults.headers.common['X-Requested-With'];
    $interpolateProvider.startSymbol('{[{');
    $interpolateProvider.endSymbol('}]}');
}]);
general_app.controller("base", function($scope,$http) {
	$scope.flag=1;$scope.option=1;
	console.log($scope.option);
	$scope.height = window.innerHeight;
	$scope.teamMembers = [
							[
								{'name':'Sourya', 'module':'Mechanical Lead', 'description':'Sourya.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Akshit', 'module':'Electrical Lead', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Ajit', 'module':'Spons and PR Lead', 'description':'Ajit.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Manish', 'module':'Mentor', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Akshay', 'module':'Manipulator', 'description':'Akshay.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Abhijeet', 'module':'Locomotion', 'description':'Abhijeet.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'}
							],
							[
								{'name':'Ridhi', 'module':'Power', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Sankalp', 'module':'Main control board', 'description':'Sankalp.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Saurav', 'module':'Gripper', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Ganga', 'module':'Software', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Gaurav', 'module':'Communications', 'description':'Gaurav.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Aniket', 'module':'Software', 'description':'Aniket.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'}
							],
							[
								{'name':'Nikhil', 'module':'Chassis', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Adarsh', 'module':'Science', 'description':'Adarsh.jpg', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Uthej', 'module':'Chassis', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Suganthan', 'module':'Chassis', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Achu', 'module':'Software', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'},
								{'name':'Shashank', 'module':'Elecrical', 'description':'profile.png', 'flink':'flink', 'tlink':'tlink', 'glink':'glink'}
							],
						];
});
