# VS-code

{
	"workbench.editor.enablePreview": false, //打开文件不覆盖
	"search.followSymlinks": false, //关闭rg.exe进程
	"files.autoSave": "afterDelay", //打开自动保存
	"terminal.integrated.rendererType": "dom",
	"editor.insertSpaces": false,
	"sync.gist": "ab7dd2715ba46155605eb4cb18677351",
	"sync.autoDownload": false, // 配置
	"element-helper.language": "zh-CN",
	"wxmlConfig.onSaveFormat": true, // "wxml保存自动格式化
	"element-helper.version": "2.5",
	"element-helper.indent-size": 2,
	"element-helper.quotes": "double",
	// html vue qoutes
	"element-helper.pug-quotes": "single", // jade/pug quotes
	// "workbench.colorTheme": "Kimbie Dark"
	"files.associations": {
		"*.vue": "vue",
		"*.html": "html",
		"*.njk": "nunjucks",
		"*.wxss": "css"
	},
	"files.exclude": {
		"**/.idea": true,
		"**/yarn.lock": true,
		"**/tmp": true,
		"**/.classpath": true,
		"**/.project": true,
		"**/.settings": true,
		"**/.factorypath": true,
		"**/.git": false,
		"**/.svn": true,
		"**/.hg": true,
		"**/CVS": true,
		"**/.DS_Store": true
	},
	"files.trimTrailingWhitespace": true,
	"files.insertFinalNewline": true,
	"files.trimFinalNewlines": true,
	"search.exclude": {
		"**/dist": true,
		// "**ild": true,
		"**/elehukouben": true,
		"**/.git": true,
		"**/.gitignore": true,
		"**/.svn": true,
		"**/.DS_Store": true,
		"**/.idea": true,
		"**/.vscode": false,
		"**/yarn.lock": true,
		"**/tmp": true
	},
	"editor.cursorBlinking": "smooth",
	"editor.multiCursorModifier": "ctrlCmd",
	"editor.formatOnPaste": true,
	"editor.fontSize": 12,
	"editor.tabSize": 2,
	"editor.lineHeight": 24,
	"editor.renderLineHighlight": "none",
	"editor.renderWhitespace": "none",
	"editor.snippetSuggestions": "top",
	"editor.renderIndentGuides": false,
	// vscode默认启用了根据文件类型自动设置tabsize的选项
	"editor.detectIndentation": false,
	// 重新设定tabsize
	"editor.minimap.enabled": false,
	//关闭快速预览
	"editor.minimap.renderCharacters": false,
	"editor.codeLens": true,
	"editor.fontLigatures": true,
	// jsx自动修复有问题，取消js的format
	"editor.formatOnSave": true,
	"editor.lineNumbers": "on",
	//开启行数提示
	"editor.tabCompletion": "on",
	"editor.quickSuggestions": {
		//开启自动显示建议
		"other": true,
		"comments": true,
		"strings": true
	},
	"editor.formatOnType": false,
	"editor.fontFamily": "Consolas, 'Courier New', monospace,Avenir, 'Chinese Quote', -apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', 'Helvetica Neue', Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'",
	"breadcrumbs.enabled": true,
	// 配置emmet是否启用tab展开缩写
	"emmet.triggerExpansionOnTab": true,
	// 配置emmet对文件类型的支持，比如vue后缀文件按照html文件来进行emmet扩写
	"emmet.syntaxProfiles": {
		"vue-html": "html",
		"vue": "html",
		"javascript": "javascriptreact",
		// xml类型文件默认都是单引号，开启对非单引号的emmet识别
		"xml": {
			"attr_quotes": "single"
		}
	},
	// 在react的jsx中添加对emmet的支持
	"emmet.includeLanguages": {
		"jsx-sublime-babel-tags": "javascriptreact"
	},
	"javascript.validate.enable": true,
	"typescript.format.enable": true,
	"typescript.format.insertSpaceBeforeFunctionParenthesis": true,
	// "tslint.autoFixOnSave": true,
	"javascript.format.insertSpaceBeforeFunctionParenthesis": true,
	"javascript.format.insertSpaceAfterSemicolonInForStatements": true,
	"javascript.format.enable": true,
	"javascript.format.insertSpaceBeforeAndAfterBinaryOperators": true,
	"javascript.format.insertSpaceAfterKeywordsInControlFlowStatements": true,
	"javascript.format.insertSpaceAfterCommaDelimiter": true,
	"javascript.format.insertSpaceAfterConstructor": false,
	"javascript.format.placeOpenBraceOnNewLineForControlBlocks": false,
	"[jsonc]": {
		"editor.defaultFormatter": "vscode.json-language-features"
	},
	"vetur.format.defaultFormatterOptions": {
		"html": "prettier",
		"css": "prettier",
		"postcss": "prettier",
		"scss": "prettier",
		"less": "prettier",
		"js": "prettier",
		"ts": "prettier",
		"stylus": "stylus-supremacy",
		"js-beautify-html": {
			"wrap_attributes": "force-expand-multiline"
		}
	},
	"vetur.validation.template": true,
	"vetur.format.defaultFormatter.html": "js-beautify-html",
	// "vetur.format.defaultFormatter.js": "prettier",
	"vetur.format.defaultFormatter.js": "vscode-typescript",
	// 格式化stylus, 需安装Manta's Stylus Supremacy插件
	"stylusSupremacy.insertColons": false,
	// 是否插入冒号
	"stylusSupremacy.insertSemicolons": false,
	// 是否插入分好
	"stylusSupremacy.insertBraces": false,
	// 是否插入大括号
	"stylusSupremacy.insertNewLineAroundImports": false,
	// import之后是否换行
	"stylusSupremacy.insertNewLineAroundBlocks": false,
	"prettier.printWidth": 120,
	"prettier.semi": false,
	"prettier.singleQuote": true,
	"eslint.enable": true,
	"eslint.autoFixOnSave": true,
	"eslint.validate": [
		"javascript",
		"javascriptreact",
		"typescript",
		"typescriptreact",
		"vue",
		"html",
		{
			"language": "html",
			"autoFix": true
		},
		{
			"language": "vue",
			"autoFix": true
		}
	],
	// eslint配置文件
	"eslint.options": {
		"plugins": [
			"vue",
			"html",
			"standard",
			"promise",
			"node",
			"react",
			"jsx-a11y"
		]
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode",
		"editor.formatOnSave": false
	},
	"[css]": {
		"editor.defaultFormatter": "michelemelluso.code-beautifier"
	}
}