


# test

```
    override fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View? {
        val binding = FragmentTestBinding.inflate(inflater)
        val adapter = TestAdapter()
        binding.recyclerView.adapter = adapter
        binding.test = TestViewModel(adapter)
        binding.recyclerView.layoutManager = LinearLayoutManager(context)
        return binding.root
    }
```


---

# test2
