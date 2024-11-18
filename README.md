진짜 기본적인 사용법. 단순 텍스트 전달하기 정도 + 애니메이션

 binding.btn.setOnClickListener {
    val bundle = bundleOf("user_input" to binding.et.text.toString())
    
    findNavController().navigate(R.id.action_homeFragment_to_secondFragment, bundle)
}
