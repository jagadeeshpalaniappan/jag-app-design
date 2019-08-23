# jag-app-design

## App Design Options

```js

const backend = {
	'AppArchitecture': ['Microservices', 'Serverless', 'SOA', 'Monolith'],
	'API Design Pattern': ['REST', 'GraphQL', 'Webhooks', 'Websockets', 'gRPC', 'SOAP'],
	'Stack': {
		'Node': ['Node.js', 'Express'],
		'Java': ['Java', 'Spring Boot'],
		'Python': ['Python', 'django']
	},
	'Database': {
		'NoSQL': ['MongoDB', 'Cassandra'],
		'SQL': ['PostgreSQL', 'MySQL']
	},
	'Cache': ['Redis', 'Memcached']
};


const frontend = {
	'Web': {
		'JS Framework': ['React', 'Angular', 'Vue', 'Angular.js', 'Polymer'],
		'Data Management': ['Redux', 'ReactiveX'],
		'CSS Framework': ['Bootstrap', 'Ant Design', 'Material', 'Foundation', 'Primer CSS'],
		'Browser Cache': ['IndexedDB', 'LocalStorage', 'SessionStorage', 'Cookies']
	},
	'Mobile': ['React Native'],
	'Desktop': ['Electron', 'React Native Desktop']
};

const infra = {
	'Cloud': {
		'IaaS': ['AWS', 'GCP', 'Azure'],
		'PaaS': ['CloudFoundry', 'Dockers & Kubernetes']
	},
	'OnPrem': {
		'Unix': ['Ubuntu']
	}
};


const baseFeatures = {
	'AuthManagementSystem(AMS)': {
		'IAM': ['Auth0', 'UAA', 'Amazon Cognito', 'AWS IAM', 'GCP IAM']
	},
	'TenantManagementSystem(TMS)': ['Multi Tenancy', 'Cross Tenant Access', 'Per Tenant -DB', 'Per Tenant -Auth'],
	'UserManagementSystem(UMS)': ['User CRUD'],
	'FeatureManagementSystem (FMS)': []
};

const app = build(infra, frontend, backend, baseFeatures);


```

