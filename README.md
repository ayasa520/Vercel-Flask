# Vercel-Flask
用 Vercel 部署 Flask App 的尝试

参考了 [How to deploy a Python/Flask App to Vercel - DEV Community](https://dev.to/andrewbaisden/how-to-deploy-a-python-flask-app-to-vercel-2o5k)

实际上并不需要严格按照他的流程，只要保证 `requirements.txt` , `index.py` 和 `vercel.json` 在根目录即可.

部署的结果: [https://vercel-flask-nu.vercel.app](https://vercel-flask-nu.vercel.app/)

ps: 我获取的 Flask 版本为 2.0.1, 但是 `requirements.txt` 中写 `flask==2.0.1` 部署会失败, 改为 `1.1.2` 则正常
