
## Full Stack App Design -Options

```js
const backend = {
	'Architecture': ['Microservices', 'Serverless', 'SOA', 'Monolithic'],
	'API Design': ['REST', 'GraphQL', 'Webhooks', 'Websockets', 'gRPC', 'SOAP'],
	'Stack': {
		'Node': {
			'API': ['Express'],
			'Versions': ['ES6', 'ES5', 'TypeScript'],
			'Build Tools': ['WebPack', 'Gulp', 'Grunt'],
			'Package Manager': ['NPM']
		},
		'Java': {
			'API': ['Spring Boot'],
			'Versions': ['Java8', 'Java7'],
			'Build Tools': ['Maven', 'Ant'],
			'Package Manager': ['Maven']
		},
		'Python': {
			'API': ['django'],
			'Build Tools': ['...'],
			'Package Manager': ['...']
		}
	},
	'Database': {
		'NoSQL': ['MongoDB', 'Cassandra'],
		'SQL': ['PostgreSQL', 'MySQL']
	},
	'Cache': ['Redis', 'Memcached'],
	'Message Broker': ['Kafka', 'RabbitMQ', 'Redis-Pub/Sub'],

};

const frontend = {
	'Web': {
		'AppArchitecture': ['Single Page App', 'Server Side Rendering', 'MicroFrontends', 'Monolith'],
		'JS Framework': ['React', 'Angular', 'Vue', 'Angular.js', 'Polymer'],
		'Data Management': ['Redux', 'ReactiveX', 'Pub/Sub'],
		'JS Versions': ['ES6', 'ES5', 'TypeScript'],
		'CSS Framework': ['Bootstrap', 'Ant Design', 'Material', 'Foundation', 'Primer CSS'],
		'Browser Cache': ['IndexedDB', 'LocalStorage', 'SessionStorage', 'Cookies'],
		'Build Tools': ['WebPack', 'Gulp', 'Grunt'],
		'Package Manager': ['NPM', 'Bower', 'JSPM']
	},
	'Mobile': ['React Native'],
	'Desktop': ['Electron', 'Nativefier', 'React Native Desktop']
};

const infra = {
	'Cloud': {
		'IaaS': ['AWS-EC2', 'GCP-GoogleComputeEngine', 'Azure'],
		'PaaS': ['Zeit', 'Netlify', 'CloudFoundry', 'Dockers & Kubernetes', 'GCP-GoogleAppEngine',],
		'ServerLess': ['Lambda', 'Google Cloud Functions', 'Azure serverless']
	},
	'OnPrem': {
		'Unix': ['Ubuntu']
	},
	'CI/CD': ['Jenkins', 'CircleCI', 'Github Actions'],
	'VCS': ['Github', 'GitLab', 'BitBucket']
};

const app = build(infra, backend, frontend);
```

### App Features
```js
const baseFeatures = {
	'AuthManagementSystem(AMS)': {
		'IAM': ['Auth0', 'UAA', 'Amazon Cognito', 'AWS IAM', 'GCP IAM']
	},
	'TenantManagementSystem(TMS)': ['Multi Tenancy', 'Cross Tenant Access', 'Per Tenant -DB', 'Per Tenant -Auth'],
	'UserManagementSystem(UMS)': ['User CRUD'],
	'FeatureManagementSystem (FMS)': []
};
app.addFeature(baseFeatures);

```

